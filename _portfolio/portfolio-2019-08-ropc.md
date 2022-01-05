---
title: "ropc"
excerpt: 'A Turing-complete ROP compiler with a shellcode stack, presented at BSidesLV 2019.'
collection: portfolio
---

__ropc__ is a compiler from _Turing-complete ROPC-IR_ to x86-64 shellcode. ROPC-IR is an assembly-like source language of my own invention. The most distinguishing feature of my compiler is that the shellcode program has access to a 2nd stack, called the _shellcode stack_. Once you have a shellcode stack, much becomes possible, such as subroutine calls within shellcode as well as library calls that don't mangle the shellcode on the target stack.

<a href="https://github.com/nmosier/rop-tools">GitHub</a>

## Conference Talk
I presented my talk at the BSides Las Vegas 2019 security conference:

<p style="text-align: center;"><i>
ROP With a 2nd Stack <br />
- or - <br />
This Exploit is a Recursive Fibonacci Sequence Generator
</i>
<br />
<br />
<a href="/files/ropc-slides.pdf">Slides</a> &bull; <a href="/files/ropc-talk.mp4">Video</a>

</p>
