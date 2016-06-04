# Crystal Instructions

## Additional Installation

1.  install Crystal (tested with version 0.17.4)

## llvm

``` sh
# compile to llvm ir
crystal build --emit=llvm-ir --single-module hello.cr
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
