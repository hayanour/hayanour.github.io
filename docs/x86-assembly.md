---
layout: default
title: x86 Assembly 
parent: All Notes
nav_exclude: true
---

# Assembly
## Basic Structure
Basic structure of an assembly (`.s`) program that doesn't crash:
```nasm
.intel_syntax noprefix

mov rax, 60
syscall
```

## Assembling and Linking Programs
Assemble and link an assembly source code into an executable:
```shell
as <sourceName>.s && ld a.out -o <executableName>
```
