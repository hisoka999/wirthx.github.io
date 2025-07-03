---
title: Quickstart Guide
permalink: /docs/quickstart/
---

# Your first program

## Hello World

```pascal
program hello;
begin
    writeln('Hello World');
end.
```

## Compiling the program
To compile a pascal program you do not need a separate project file. The compiler will try to determin all dependencies and build the program. The binary of the compiler can be executed with the command `wirthx`. The Output will be defined by the first line.

```sh
wirthx hello.pas
```

## Starting th program
Since the compiler generated a native

### Unix
```sh
./hello
```

### Windows
```cmd
./hello.exe
```
