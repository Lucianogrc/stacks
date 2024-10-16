cmake_minimum_required(VERSION 3.28)
project(stacks)

set(CMAKE_CXX_STANDARD 17)

add_executable(stacks main.cpp
        cmake-build-debug/Stack.cpp
        cmake-build-debug/Stack.h)
