---
layout: default
title: Bash String Manipulation
parent: All Notes
nav_exclude: true
---

# Bash String Manipulation

## Base64 Decode
From stdin:
```bash
echo "c29tZXN0cmluZw==" | base64 -d
```
Or from a file:
```bash
base64 -d encoded_file.txt
```

## Reverse a String
From stdin: 
```bash
echo "hello" | rev
# output: olleh
```
Or from a file:
```bash
rev original.txt
```

## View Hex as Decimal
```bash
echo $((0x16))

```
