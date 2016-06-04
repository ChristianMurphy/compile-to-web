# Swift Instructions

## Additional Installation

1.  install [Swift](https://swift.org/download/) (tested with version 2.2.1)

## llvm

``` sh
# compile to llvm ir
swiftc --emit-ir hello.swift -o hello.ll
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
