# Swift Instructions

## Installation

1.  install swift (tested with version 2.2.1)

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

## Web Assembly

TODO
