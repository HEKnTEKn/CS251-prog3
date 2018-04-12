cmake_minimum_required(VERSION 3.8)
project(Prog3)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Prog3/src/bst.h
        Prog3/src/test.cpp)

add_executable(Prog3 ${SOURCE_FILES})