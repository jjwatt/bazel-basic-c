# WIP
# Basic Bazel C Starter repo
Keep the main branch at "modern" best practices (as best we can tell from an outsider's perspective).

There are actually mutliple ways to do this.

1. Compile with a C++ toolchain & C externs
2. Compile with a real C toolchain

The main goal of this repo is to show how to do this with a real C toolchain, but I may offer alternative examples in the main branch or a different branch.

The first draft of this shows compiling main with `extern "C"`. You can surround your C code with this (you actually don't really need it for main, iiuc). And you can mix C and C++ this way.

I'll do a different repo or a different branch that illustrates how to use a real gcc or muscl plain C toolchain.

The C++ version of this starter repo is here: https://github.com/jjwatt/bazel-basic-cpp

