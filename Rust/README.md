# Rust Instructions

## Installation

1.  install emscripten
2.  install rust
3.  install Node.js

## Build

``` sh
rustc --emit=llvm-ir hello.rs
emcc hello.ll
```

## Run

``` sh
node a.out.js
```

## Tested With

*   emscripten 1.36.5
*   rustc 1.9.0
*   node 6.2.0
