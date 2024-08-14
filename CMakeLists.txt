cmake_minimum_required(VERSION 3.28)
project(vice C)

set(CMAKE_C_STANDARD 11)

add_executable(vice vice.c
        defs.h
        init.c)
