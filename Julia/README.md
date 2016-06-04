# Julia Instructions

## Additional Installation

1.  install [Julia](http://julialang.org/downloads/) (tested with version 0.4.5)

## llvm - broken

``` sh
# compile to llvm bc
julia --compile=all --output-bc=hello.bc hello.jl
```

## asm.js - unknown

``` sh
# compile to asm.js
emcc hello.bc
# run code
node a.out.js
```

## Web Assembly - unknown

``` sh
# compile to llvm object
llc hello.bc -march=wasm32 -filetype=asm -o hello.s
# compile to web assembly
s2wasm hello.s > hello.wast
```
