# Crystal Instructions

## Installation

1.  install emscripten
2.  install crystal
3.  install Node.js

## Currently Broken

Crystal Language issue 535 is tracking progress.

## Build

``` sh
crystal build --emit=llvm-ir --single-module hello.cr
emcc hello.ll
```

## Run

``` sh
node a.out.js
```

## Tested With

*   crystal 0.17.4
*   emscripten 1.36.5
*   node 6.2.0
