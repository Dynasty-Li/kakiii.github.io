---
layout:     post
title:      CSE101 Lecture 3 Possible Answers
subtitle:   Could be wrong, just for reference.
date:       2019-09-17

author:     KaKi
header-img: img/post-bg-code.jpeg
catalog: true
tags:
    - XJTLU
    - CSE101
    - Answers
    - Y2
---

## 👴又回来啦

一拖更就是一个半月，今天终于开始填坑了（Lec2是啥我怎么啥都不知道啊）。

### Name 4 examples of HLLs.

Java, Python, C, C++……

### Translation fills in the semantic gap in computer systems. (True of false?)

True

### Name 3 different ways of translation. Identify the crucial role of translation under each. 

Intrepreter, Assembler, Compiler(后面一个不太明白)

### When compile-time errors occur, what do we do?

Check the source code and revise it.(猜的)

### What are the purposes of linking?

refer data or subroutines in another module.

### ‘Loading’ is carried out before ‘linking’ after a program is compiled. (True or false?)

False.

### Program modules can be compiled separately.(True or false?)

True.

### A compiler can translate a module into binary codes, but it cannot resolve those references to other modules. This occurs when …?

linker doesn't begin to work

### Library files are usable if linked into your program code. (True or false?)

True.

### Interpreters typically convert program code into what?

an intermediate form, consisting of tokens

### What is the output of program compilation?

machine code.

### Name 2 scenarios where interpreters are more useful than compilers.

    – Interpreters are more accurate in terms of error reporting.
    – Interpretation can provide uniform execution environment across several diverse computers. (Portable)

### Interpreters are sometimes called as virtual machine because … ?

They take one instruction at a time and execute it.

### Mention 3 approaches to code sharing.

    – Source-level subroutines and macro libraries.
    – Pre-translated re-locatable binary libraries.
    – Dynamic libraries and dynamic linking.

### Name 2 disadvantages (or issues) of macro libraries.

    the answer of the following question:
    – Who owned the code?
    – Who should maintain it?

### Libraries can be linked into your program code, but not altered. (True or false?)

False.

### What are the disadvantages of program execution with pre-translated program library?

Each program is to have a private copy of the subroutines, wasting valuable memory space, and swapping time, in a multitasking system.

### There exists a de-facto standard of dynamic libraries and dynamic linking. (True or false?)

True. Microsoft’s ActiveX
