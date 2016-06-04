# Haskell Instructions

1.  Install [Haskell](https://www.haskell.org/downloads)
    (tested with version Version 7.10.3)

## llvm

``` sh
# compile to llvm ir
ghc -fllvm -keep-llvm-files -fforce-recomp hello.hs
```

## asm.js - broken

``` sh
# compile to asm.js
emcc hello.bc
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
