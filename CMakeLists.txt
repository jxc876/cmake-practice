cmake_minimum_required(VERSION 3.31)
project(helloworld C)

set(CMAKE_C_STANDARD 17)

add_executable(helloworld hello.c)
add_executable(goodbye goodbye.c)
