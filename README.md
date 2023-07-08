# psef
PSEF (Portable SPWN Executable Format) - an executable file format for writing code in any language and running it in SPWN

# Usage
See [samples](./samples) folder.

# Instruction Set
- NOP: 0 (no operation)
- CONST: 1 (pushes value onto stack)
- ADD: 2 (adds two values on stack)
- PRINT: 3 (prints topmost value on stack)
- LOAD: 4 (loads variable onto stack)
- SET: 5 (sets a variable's value)
- CLONE: 6 (siilar to `set`, except the value is not popped from stack and instead cloned)
- RET: 7 (returns topmost value on stack)
- INPUT: 8 (gets user input and pushes result onto stack)
- FMT: 9 (formats a string with a substring)
- (not available): 10 (not an instruction, used by compiler & parser as marker)
- INIT: 11 (creates a new variable with an empty value)
