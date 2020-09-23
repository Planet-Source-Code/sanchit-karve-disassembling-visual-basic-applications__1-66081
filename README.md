<div align="center">

## DISASSEMBLING VISUAL BASIC APPLICATIONS


</div>

### Description

As long as you know Assembly Language, it is easy to read disassembled listings

of executable files written in C/C++ or PASCAL, especially if you are using

IDA Pro as your disassembler. This is so because C and C++ Compilers generate

(or at least try to) efficient code. Some Compilers like Borland C++ use simple

instructions for complex operations(also remember that this is not always the

case) which make it easier to study them. Implementation of Code Constructs such

as loops, IF statements, Ternary IF statements, switch constructs etc. can be

found very easily as each one is unique and distinct.

However the same is not true for Applications written in Visual BASIC. VB

Programs are said to be very slow and hence deliver poor performance. There is a

reason for this. Visual BASIC programs unlike those written in other languages

don't use Windows API Directly. Local functions present in VB Runtime Files are

called which call functions from the Windows API.Most of the Visual BASIC

functions are present in MSVBM60.DLL (if you've got Runtime Files ver. 6.0).

So to study VB programs, we must disassemble and analyze the MSVBM60.DLL file as

well.

Since VB programs use such a complex API Function call procedure, programs tend

to run slower.(There are other reasons as to why VB programs run slower but I

won't be covering it as it's off-topic.)

It becomes difficult to analyze VB Programs as it uses functions which are not

part of the Windows API and hence we are not acquainted with them.

My primary aim in this Tutorial is to teach the reader how to understand

disassembled listings of programs written in Visual BASIC.

My secondary aim is to help you realise why Visual BASIC is not suitable for

writing small,fast and efficient programs.

Almost all authors of Visual BASIC books mention that Visual BASIC does not

give you applications with good performance.

This tutorial tells you why.

The Tutorial will talk about executable files compiled in Visual BASIC in

Native Code ONLY and not p-code.

After reading this tutorial, you should be able to disassemble,debug and

understand Visual Basic Applications. You may also be able to reverse engineer

Protection Mechanisms written in Visual BASIC.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |2006-07-26 07:20:02
**By**             |[Sanchit Karve](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sanchit-karve.md)
**Level**          |Intermediate
**User Rating**    |4.9 (34 globes from 7 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[DISASSEMBL2008867262006\.zip](https://github.com/Planet-Source-Code/sanchit-karve-disassembling-visual-basic-applications__1-66081/archive/master.zip)








