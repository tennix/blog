title: 初探 Rust FFI
date: 2015-07-25 00:22:11
tags: [rust, ffi, cargo]
---

``c
#include <stdio.h>

void say_hello(char* name) {
    printf("Hello, %s\n", name);
}
``