# Swift Instructions

## Installation

1.  install emscripten
2.  install swift
3.  install Node.js

## Currently Broken

emscripten issue 2427 is tracking progress

## Build

``` sh
swiftc --emit-ir hello.swift > hello.ll
emcc hello.ll
```

## Run

``` sh
node a.out.js
```

## Tested With

*   emscripten 1.36.5
*   swift 2.2.1
*   node 6.2.0
