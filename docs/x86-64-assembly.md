---
layout: default
title: x86-64 Assembly 
parent: All Notes
nav_exclude: true
---

# x86-64 Assembly
## Basic Structure
Basic structure of an assembly (`.s`) program that exits 0:
```nasm
.intel_syntax noprefix

mov rax, 60
xor rdi, rdi
syscall
; Comments start with semicolon.
```

## Assembling and Linking Programs
Assemble and link an assembly source code into an executable:
```shell
as <sourceName>.s && ld a.out -o <executableName>
```
