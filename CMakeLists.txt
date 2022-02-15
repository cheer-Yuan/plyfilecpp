cmake_minimum_required(VERSION 3.21)
project(plyfilecpp)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(plyfilecpp
        main.cpp
        main.h)
