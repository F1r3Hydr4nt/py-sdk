# ASM Comparison
1. Clone all relevant repos
    - Python
    - TS
    - Go
    - Teranode
2. Install requirements/Setup each project repo
3. Run tests in each
4. Choose a ground truth implementation (Teranode?)
5. Make a decision (Teranode)
6. Chronicle opcodes(?)

## Chronicle Opcodes
OP_VER
OP_VERIF
OP_VERNOTIF
OP_SUBSTR
OP_LEFT
OP_RIGHT
OP_2MUL
OP_2DIV

## Progress Report
1. Chronicle opcodes defined in ALL repos but disabled in some e.g: ts-sdk
2. Teranode repo contains script_utils_test.go
3. Teranode devs have made an executive decision to remove OP_TRUE & OP_FALSE

## Implementation
1. Checkout new branch op-standardise
2. Fixing test warnings
3. 

## Plan
1. Propose this standardisation across the board?
2. Implement Chronicle opcodes in each library?