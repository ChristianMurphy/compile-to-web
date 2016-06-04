# Julia Instructions

## Installation

1.  install emscripten
2.  install julia
3.  install Node.js

## Currently Broken

cannot open boot.jl

## Build

``` sh
julia --compile=all --output-bc=hello.bc hello.jl
emcc hello.bc
```

## Run

``` sh
node a.out.js
```

## Tested With

*   julia 0.4.5
*   emscripten 1.36.5
*   node 6.2.0
