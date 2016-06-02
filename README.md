# brus
brus is a procedural noise library capable of producing value noise, worley noise, cell noise and fractal sum versions of those.

The library is targeted towards VFX & Games and other image processing heavy applications. It is also intended to be very easy to integrate and provide the bulk of needed operations. In this regard it is inspired by the stb single file libraries.

brus is Swedish for "noise".

## Technical details
The library targets C99. The rationale for this is that C99 is decently supported by all the popular compilers (for MSVC 2013 and onwards.) 

## Licensing
The main library code (`brus.h` and `brus.c`) is released under MIT license as well as the utilites `brusimg.c`.
