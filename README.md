# Makefile Tutorial with a Simple C program split across multiple files
- Project contains main.c, math_utils.h and math_utils.c

## math_utils.h
- This file contains function declarations (not definitions).

## math_utils.c
- This file contains the actual function definitions.

## main.c
- This file uses the functions defined elsewhere

## Key rules to remember
- `.h` for declarations
- `.c` for definitions
- `main.c` includes headers, not `.c` files
- Compile all `.c` files together

## You can take this further
- Add global variables across files
- Use static or extern
- Convert this to an embedded-style project
- Use Makefiles to handle multi-file builds