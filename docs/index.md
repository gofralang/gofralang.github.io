## Gofra
- [Documentation](https://github.com/gofralang/core/blob/main/DOCUMENTATION.md), [Examples](https://github.com/gofralang/core/tree/main/examples), [GitHub](https://github.com/gofra-lang)

## Features
- Interpretate code (Will removed with isolated VM/Bytecode interpretation).
- Generate graph for the code ('.dot' graphviz)(May be removed later as redundancy).
- Compile (Generate) python code (GOFRA -> Python) (May be also removed later as redundancy or part of Bytecode2Python).
- Lint (Type check) [WIP].
- Bytecode (Compile, Interpretate) [WIP]

## Language features
- Stack implementation (push, pop)
- Conditional IFs ([bool_from_stack] if [code] else [code] end).
- WHILE loops (while [expression] do [code] end)
- Bytearray Memory (mbwrite, mbread, mbshowc, mbptr etc...)
- Characters, Strings.
- Basic I/O.

### Examples
```go
35 // Push 35 in the stack.
5 // Push 5 in the stack.
+ // Pop both 35 and 5, and push their sum in the stack.
show // Pop value from the stack and show it on the screen.
```
```go
"Hello, World!" mshowc
```
