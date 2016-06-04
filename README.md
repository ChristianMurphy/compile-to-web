# Compile to Web - Language Support

The goal of this project is to see what languages can be compiled into asm.js
and web assembly (WASM)

## Languages

| Language                     | Instructions       | Compiles to LLVM   | LLVM compiles to asm.js | LLVM compiles to WASM |
|------------------------------|:------------------:|:------------------:|:-----------------------:|:---------------------:|
| [C](C/README.md)             | :white_check_mark: | :white_check_mark: | :white_check_mark:      | :white_check_mark:    |
| [C++](C++/README.md)         | :white_check_mark: | :white_check_mark: | :white_check_mark:      | :white_check_mark:    |
| [Crystal](Crystal/README.md) | :white_check_mark: | :white_check_mark: | :no_entry:              | :no_entry:            |
| [Go](Go/README.md)           | :white_check_mark: | :question:         | :question:              | :question:            |
| [Java](Java/README.md)       | :white_check_mark: | :question:         | :question:              | :question:            |
| [Julia](Julia/README.md)     | :white_check_mark: | :no_entry:         | :question:              | :question:            |
| [Python](Python/README.md)   | :question:         | :question:         | :question:              | :question:            |
| [Rust](Rust/README.md)       | :white_check_mark: | :white_check_mark: | :no_entry:              | :no_entry:            |
| [Swift](Swift/README.md)     | :white_check_mark: | :white_check_mark: | :no_entry:              | :no_entry:            |

### Key

| Icon               | Meaning |
|:------------------:|---------|
| :white_check_mark: | Success |
| :no_entry:         | Broken  |
| :question:         | Unknown |

## Installation

1.  install [emscripten](https://kripken.github.io/emscripten-site/docs/getting_started/downloads.html)
    (tested with version 1.36.5)

2.  install [binaryen](https://github.com/kripken/emscripten/wiki/WebAssembly#building-webassembly-now)
    (tested with version 9)

3.  install [node.js](https://nodejs.org/en/download/)
    (tested with version 6.2.0)

4.  follow additional setup for chosen language
