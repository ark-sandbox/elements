# ![Elements-Logo](docs/assets/images/elements.png) Elements C++ GUI library

[![CMake Build Matrix](https://github.com/cycfi/elements/workflows/Build/badge.svg)](https://github.com/cycfi/elements/actions?query=workflow%3ABuild)

![alt Photon Sampler](docs/assets/images/photon_sampler.jpg)

## Introduction

Elements is a lightweight, fine-grained, resolution independent, modular GUI library. Elements is designed with these requirements in mind:

1. It should be open source with a liberal, non-viral license.
2. It should be usable in any application and should play well with other GUI
   libraries and frameworks.
3. Corollary to the second requirement is that it can also be used to develop
   plugins. It should not own the event loop and should be able to co-exist
   with components within a plugin host such as VST and AU.
4. It should be resolution independent and allow for HDPI displays.
5. Should not rely on a “visual” GUI editor or code generator.
6. It should have a declarative API using modern C++. Declarative C++ code
   tells you *what* rather than *how* (imperative). The GUI should be
   declared in C++ code.

Elements, is extremely lightweight… and modular. You compose very
fine-grained, flyweight “elements” to form deep element hierarchies using a
declarative interface with heavy emphasis on reuse.

## News

- 12 August 2019: Windows port completed
- 01 September 2019: Linux port completed
- 22 February 2020: Improved font support
- 23 February 2020: Setup and Installation guide updated for Windows and Linux.

## Setup and Installation

The Elements C++ GUI library is cross-platform. Elements currently supports
the MacOS, Windows and Linux. Follow the [Setup and Installation
guide](http://cycfi.github.io/elements/setup) to get started using the
library.

## Design Aspects

The Elements C++ GUI library is 1) Modular, 2) Declarative, and 3)
Interoperable. This document explains these three key [Design
Aspects](http://cycfi.github.io/elements/aspects) behind Elements through
examples.

## Gallery

Follow this link for more screenshots: [Gallery](http://cycfi.github.io/elements/gallery).

## <a name="jdeguzman"></a>About the Author

Joel got into electronics and programming in the 80s because almost
everything in music, his first love, is becoming electronic and digital.
Since then, he builds his own guitars, effect boxes and synths. He enjoys
playing distortion-laden rock guitar, composes and produces his own music in
his home studio.

Joel de Guzman is the principal architect and engineer at [Cycfi
Research](https://www.cycfi.com/) and a consultant at [Ciere
Consulting](https://ciere.com/). He is a software engineer specializing in
advanced C++ and an advocate of Open Source. He has authored a number of
highly successful Open Source projects such as
[Boost.Spirit](http://tinyurl.com/ydhotlaf),
[Boost.Phoenix](http://tinyurl.com/y6vkeo5t) and
[Boost.Fusion](http://tinyurl.com/ybn5oq9v). These libraries are all part of
the [Boost Libraries](http://tinyurl.com/jubgged), a well respected,
peer-reviewed, Open Source, collaborative development effort.

-------------------------------------------------------------------------------

*Copyright (c) 2014-2020 Joel de Guzman. All rights reserved.*
*Distributed under the [MIT License](https://opensource.org/licenses/MIT)*
