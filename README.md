# Port of OS/2 opengl auxdemos to fpc


## Requirements
- fpc 3.2.2 (full install)
- OS/2 Warp 4.5 or later
- OpenGL 1.1.0 ("Gold"; 1.0.0 might also do)
- libaux.dll (57184 okt 21 1997) (in lib)
- OS2TK45 (Toolkit) samples/demos


## How to compile:
- see script prog\MALL.CMD  

One program does not compile.

## How to run:
- see script prog\XALL.CMD  

Four programs don't run:
- antiindx.exe
- antipidx.exe
- fogindex.exe
- maplight.exe  

Note that the originals of these don't run either.


## Motivation for this project
Write a Pascal interface for libaux.dll
