---
tags: [ecosystem]
---

# Graphics

## 2D

* [Wall](https://github.com/let-def/wall):
Vector drawing library using OpenGL as the backend.
  * [Presentation on Wall at ICFP](https://www.youtube.com/watch?v=bQB8kBkHxjk)
* [archimedes](http://archimedes.forge.ocamlcore.org/):
2D plotting library.
* [cairo2](https://github.com/Chris00/ocaml-cairo):
Bindings to Cairo, a 2D Vector Graphics Library. Integrates well with lablgtk.
* [Vg](https://github.com/dbuenzli/vg):
Declarative 2D vector graphics for OCaml.
* [TSDL](http://erratique.ch/software/tsdl):
An OCaml module providing thin bindings to the cross-platform SDL2 library.
This library uses `ctypes`,
and therefore requires less work to track changes to the C SDL libraries.
  * [tsdl-ttf](https://github.com/tokenrove/tsdl-ttf):
  Support for SDL's truetype font library.
  * [tsdl-mixer](https://github.com/tokenrove/tsdl-mixer):
  Support for the sound mixer component of TSDL.
  * [tsdl-image](https://github.com/tokenrove/tsdl-image):
  Support for the image-loading component of SDL.
* [OcamlSDL2](https://github.com/fccm/OCamlSDL2):
Bindings to the SDL2 library using C files rather than `ctypes`.
Bindings (possibly incomplete) exist also for `SDL_image` and `SDL_mixer`,
but not for `SDL_ttf`.
* [OcamlSDL](http://ocamlsdl.sourceforge.net/home.html):
Bindings to the older SDL v1.2 suite,
including `SDL_image`, `SDL_ttf`, and `SDL_mixer`.
* [imagelib](https://github.com/rlepigre/ocaml-imagelib):
Read and write various image formats. Backed by BigArrays.
* [owl_base](https://github.com/owlbarn/owl):
Part of `Owl`. This is essential for manipulating BigArrays efficiently (with vectorized operations),
for graphics and such.
* [camlimages](https://bitbucket.org/camlspotter/camlimages):
Image manipulation library for different image formats (old).

### ReasonML

* [Reprocessing](https://github.com/Schmavery/reprocessing):
A Reason 2d graphics library inspired by Processing.

## 3D

* [tgls](http://erratique.ch/software/tgls):
Thin bindings to OpenGL 3.{2,3},4.{0,1,2,3,4} and OpenGL ES {2,3}.
*This is the recommended library for OpenGL support in OCaml*.
* [glMLite](https://github.com/fccm/glMLite):
OpenGL bindings for OCaml. Provides an experimental functional API.
* [lablgl](https://github.com/garrigue/lablgl):
Interface to OpenGL. Integrates well with lablgtk.
* [glfw-ocaml](https://github.com/SylvainBoilard/GLFW-OCaml):
Bindings to [GLFW](https://www.glfw.org/), an OpenGL library providing OS-specific
functionality, such as window, surface and input management.
* [ocaml-glfw](https://github.com/rizo/ocaml-glfw):
Another library with bindings to [GLFW](https://www.glfw.org/).

## Linear Algebra

* [Owl](https://github.com/owlbarn/owl):
Numerical library, useful for fast linear algebra operations.
See [the Owl Manual](https://ocaml.xyz) for details.
* [reason-gl-matrix](https://github.com/bryphe/reason-gl-matrix):
Bindings to [glm](https://github.com/g-truc/glm),
the OpenGL linear algebra C++ library for graphics.

## Functional Reactive Programming
See [FRP](frp.md)
