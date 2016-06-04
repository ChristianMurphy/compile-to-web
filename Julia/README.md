# Julia Instructions

## Additional Installation

1.  install Julia (tested with version 0.4.5)

## llvm

``` sh
# compile to llvm bc
julia --compile=all --output-bc=hello.bc hello.jl
```

## asm.js - broken

``` sh
# compile to asm.js
emcc hello.bc
# run code
node a.out.js
```

## Web Assembly

TODO
