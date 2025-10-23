cmake_minimum_required(VERSION 3.27)
project(pl0 C)

set(CMAKE_C_STANDARD 11)

include_directories(c_base)

add_executable(pl0
        c_base/pl0.c
        c_base/pl0.h)
