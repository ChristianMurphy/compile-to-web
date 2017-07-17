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
| [Haskell](Haskell/README.md) | :white_check_mark: | :white_check_mark: | :no_entry:              | :no_entry:            |
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

1. Install vagrant
2. For a desired language `cd` into the folder, then run
``` sh
vagrant up
vagrant ssh
make
```
