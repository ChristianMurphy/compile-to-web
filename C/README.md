# C Instructions

## asm.js

``` sh
# compile to asm.js
emcc hello.c
# run code
node a.out.js
```

## Web Assembly

``` sh
# compile to wasm
emcc hello.c -s BINARYEN=1
```
