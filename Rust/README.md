# Rust Instructions

## Installation

1.  install Rust (tested with version 1.9.0)

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

## Web Assembly

TODO
