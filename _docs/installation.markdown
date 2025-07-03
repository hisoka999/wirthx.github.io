---
title: Installation
permalink: /docs/installation/
---

## Windows

**Download:** TODO

**LLVM/CLANG Download:** [https://github.com/llvm/llvm-project/releases/download/llvmorg-18.1.8/LLVM-18.1.8-win64.exe](https://github.com/llvm/llvm-project/releases/download/llvmorg-18.1.8/LLVM-18.1.8-win64.exe)

## Linux (Binarys)

### Ubuntu / Debian
```sh
wget TODO
sudo apt install wirthx-0.1.0-amd64.deb
```

### Other Distributions


```sh
wget TODO
tar xvf  wirthx-0.1.0-amd64.tgz
```

## Linux (from source)

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
