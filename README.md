# About

A simple project to practice using CMake to build C projects.

It contains two executables, each which a main function.
- `goodbye.c` — prints goodbye
- `hello.c` — prints hello

# Editor

I'm using CLion by JetBrains, good tutorial here
- https://www.jetbrains.com/help/clion/quick-cmake-tutorial.html

# Build

How to build from command line

```shell
# generate Makefile
cmake -B build . 

# run Makefile to create binaries
make -C build
```

Then run the binaries:

```shell
./build/helloworld
```

```shell
./build/goodbye
```