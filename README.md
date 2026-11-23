[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/shhovi/makefun-tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/shhovi/makefun-tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

# makefun-tiny-stack-vm-01-run-20261122

A tiny stack virtual machine for the [Build a tiny stack virtual machine](https://make.fun/bounty/tiny-stack-vm-01-run-20261122) bounty on [make.fun](https://make.fun).

`main.ts` (Node 22, stdlib only) runs every program of make.fun's tiny stack ISA in a set — 32-bit wrapping integers, a 256-value stack, calls, 256 words of memory, input/output, all ten traps with their own exit codes, and the step and output limits — and writes `/output/<id>/stdout.bin` and `/output/<id>/exit.txt` per instance.

```sh
mkdir -p out && MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts
```

Practice set: 40/40, score 1,000,000 (baseline 670,000). MIT, see [LICENSE](LICENSE).
