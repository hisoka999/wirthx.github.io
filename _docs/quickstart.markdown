---
title: Quickstart Guide
permalink: /docs/quickstart/
---

## Linux

### Cloning the repository

```sh
git clone https://github.com/hisoka999/wirthx
cd wirthx
```

## installing dependencies

You need llvm as a dependency and then g++ or clang as a compiler.

```sh
sudo apt-get update
sudo apt-get install -y llvm-18 llvm-18-dev
```


## building the compiler

### Creating a build directory

....

### Building the Compiler 

```sh
cmake -B "build" -DCMAKE_BUILD_TYPE=Release
cmake --build "build" --config Release
```

## Windows

There is no installation guide for windows available yet.
