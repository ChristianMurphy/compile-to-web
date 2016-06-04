# Rust Instructions

## Installation

1.  install [Rust](https://www.rust-lang.org/) (tested with version 1.9.0)

## llvm

``` sh
# compile to llvm ir
rustc --emit=llvm-ir hello.rs
```

## asm.js - broken

``` sh
# compile to asm.js
emcc hello.ll
# run code
node a.out.js
```

## Web Assembly - broken

``` sh
# compile to llvm object
llc hello.ll -march=wasm32 -filetype=asm -o hello.s
# compile to web assembly
s2wasm hello.s > hello.wast
```
