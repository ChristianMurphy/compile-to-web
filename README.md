# Compile to Web - Language Support

The goal of this project is to see what languages can be compiled into asm.js
and web assembly (WASM)

## Languages

| Language                      | Instructions       | Compiles to LLVM   | LLVM compiles to asm.js | LLVM compiles to WASM |
|-------------------------------|:------------------:|:------------------:|:-----------------------:|:---------------------:|
| [C](C/README.md)              | :white_check_mark: | :white_check_mark: | :white_check_mark:      | :white_check_mark:    |
| [C++](C++/README.md)          | :white_check_mark: | :white_check_mark: | :white_check_mark:      | :question:            |
| [Crystal](Crystal/README.md)  | :white_check_mark: | :white_check_mark: | :no_entry:              | :question:            |
| [Go](Go/README.md)            | :no_entry:         | :no_entry:         | :no_entry:              | :question:            |
| [Java](Java/README.md)        | :no_entry:         | :no_entry:         | :no_entry:              | :question:            |
| [Julia](Julia/README.md)      | :white_check_mark: | :white_check_mark: | :no_entry:              | :question:            |
| [Rust](Rust/README.md)        | :white_check_mark: | :white_check_mark: | :no_entry:              | :question:            |
| [Swift](Swift/README.md)      | :white_check_mark: | :white_check_mark: | :no_entry:              | :question:            |

## Installation

1.  install emscripten
2.  install binaryen
3.  install node.js
4.  follow additional setup for chosen language
