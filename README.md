# About

A simple project to practice building C projects with [CMake](https://cmake.org)

It contains two executables, each which a main function.
- `goodbye.c` — prints goodbye
- `hello.c` — prints hello

# Build with CLI

How to build from command line

```shell
# generate Makefile
cmake -B build . 

# run Makefile to create binaries
make -C build
```

The `-C` flag lets you run `make` from a different directory
- https://stackoverflow.com/questions/453447

Then run either of the binaries:

```shell
./build/helloworld
# > Hello, World!
```

```shell
./build/goodbye
# > Goodbye World!
```

# Build with IDE

I'm using CLion by JetBrains, good tutorial here
- https://www.jetbrains.com/help/clion/quick-cmake-tutorial.html
