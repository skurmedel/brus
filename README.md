# brus
brus is a procedural noise library capable of producing value noise, worley noise and fractal sum versions of those.

The library is targeted towards VFX & Games and other image processing heavy applications. It is also intended to be very easy to integrate and provide the bulk of needed operations. In this regard it is inspired by the stb single file libraries.

brus is Swedish for "noise".

## Design goals

### Soft goals
- Very easy to embed.
- Up to 4 or even arbitrary dimensions of noise.
- Should be easy to customize but provide sensible defaults.
- Reasonably quick.
- Decently tested.
- Assume there is floating point support (or at least emulated by the compiler).

### Must haves
- Must be able to lock the PRNG seed.
- Simple functions like `worley2df(coord_t x, coord_t y) -> float`.

### Desired noise types

#### Lattice
- Value noise  
- Perlin noise 
#### Point based
- Worley noise

## Using brus
Either use the make file to compile a static library, or compile the source as part of your project.

## Technical details
The library targets C++14 (VFX Platform 2018/2019).

## Licensing
The main library code (`brus.hpp` and `brus.cpp`) is released under MIT license as well as the utilites `brusimg.cpp`.
