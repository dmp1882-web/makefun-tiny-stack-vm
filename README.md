# tiny-stack-vm

A faithful interpreter of make.fun's tiny stack ISA v1 (the kit's
generator/subject/ISA.md). `main.ts` runs every program in
/input/<id>/ (program.bin + input.bin) and writes
/output/<id>/stdout.bin and /output/<id>/exit.txt.

Local run on the practice set:

    MAKEFUN_INPUT_DIR=<kit>/practice/input MAKEFUN_OUTPUT_DIR=out node main.ts

Node 22, no dependencies. MIT licensed.
