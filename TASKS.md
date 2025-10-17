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

## Plan
1. Propose this standardisation across the board?
2. Implement Chronicle opcodes in each library?

# Misc.
1. Note test results here (not seen yesterday): https://docs.google.com/spreadsheets/d/106aSWsOeNayzXOU9tRmRIvSu2Cz21YZQ5uCrwMZg1WU/edit?pli=1&gid=1111408418#gid=1111408418
2. Teranode opcode definitions in two places:
    - https://github.com/bsv-blockchain/teranode/blob/main/ui/dashboard/src/internal/utils/bitcoin-scripts.ts#L129
    - https://github.com/bsv-blockchain/teranode/blob/main/services/legacy/txscript/opcode.go#L36
3. Current Implementations:
    - Bitcoin-sv fullnode implementation.
        https://github.com/bitcoin-sv/bitcoin-sv/blob/master/src/script/opcodes.h
    - Py-sdk
        https://github.com/bsv-blockchain/py-sdk/blob/master/bsv/constants.py
    - Typescript SDK
        https://github.com/bsv-blockchain/ts-sdk/blob/master/src/script/OP.ts
    - Go SDK
        https://github.com/bsv-blockchain/go-sdk/blob/master/script/opcodes.go