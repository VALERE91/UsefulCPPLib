# UsefulCPPLib

This repositiory is simply a list of C++ librairies I often use in projects. They are quite simple to integrate as subdirectory of header only librairies in any CMake projects.

## Core guidelines

- [microsoft GSL](https://github.com/microsoft/GSL) : a must have in any modern project. It supports the C++ core guideline what is THE reference.

## String

- [fmt](https://github.com/fmtlib/fmt) : an awsome string formatting library fast and with a really clear API
- [strtk](https://github.com/ArashPartow/strtk) : a library that implement many string algorithms

## Databases

- [sqlite3](https://www.sqlite.org/index.html) : a classic amongst classic. It's a C API but pretty easy to wrap in modern C++. It contains a .c and two .h you just have to add them to your build system.

## Graphic

- [Dear ImGUI](https://github.com/ocornut/imgui) : an extremly useful little library that enable debug GUI (or simply GUI) in many graphical environnments like SDL, GLFW, Direct3D, OpenGL, Vulkan, etc. (I heavily recommend the docking branch)
- [GLFW](https://github.com/glfw/glfw) : a multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input. It goes very well with Dear ImGUI and is really simple to includei n your build system.

## Math

- [GLM](https://glm.g-truc.net/0.9.9/index.html) : a header-only library for graphical mathematics

## JSON

- [rapidjson](https://github.com/Tencent/rapidjson/) : a pretty cool librayr for JSON parsing with great performances
- [nlhomann](https://github.com/nlohmann/json) : a must-have JSON library if you have a modern compiler (what everybody should have)

## IO

- [libuv](https://github.com/libuv/libuv) : an asynchronous library that enables file, networking and multi process management (in C check UVW just after for C++)
- [UVW](https://github.com/skypjack/uvw) : a wrapper for libuv in modern C++. Must have if you need libuv and you are in modern C++

## Arguments parsing

- [cxxopts](https://github.com/jarro2783/cxxopts) : a simple library that enable the parsing of the command line arguments.

## Scripting

- [sol3](https://github.com/ThePhD/sol2) : a C++ Lua Wrapper. You will need the [lua](https://github.com/lua/lua) library but it is pretty straigthforward to integrate with CMake.

## Compression

- [LZ4](https://github.com/lz4/lz4) : one of the fastest compression/decompression library, really easy to integrate and play with

## Testing

- [Catch2](https://github.com/catchorg/Catch2) : Catch2 is my reference when I want to unit test my C++ code

## Gaming

- [EnTT](https://github.com/skypjack/entt) : Your ECS in modern C++. Already used by Mojang in Minecraft, its API is ultra modern, fast, easy to integrate and beautiful. Nothing else to say

## Logging

- [spdlog](https://github.com/gabime/spdlog) : a rather simple but extensible and ultra fast C++ logging library.
