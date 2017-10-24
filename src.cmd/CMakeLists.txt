project(Fast-Quadric-Mesh-Simplification)
cmake_minimum_required(VERSION 2.8)

#Activate c++0x flag for gcc
if(CMAKE_COMPILER_IS_GNUCC)
    set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++0x -fopenmp")
    add_definitions ("-Wall -Wno-sign-compare")
endif(CMAKE_COMPILER_IS_GNUCC)

include_directories(.)

#A simple test
add_executable(Fast-Quadric-Mesh-Simplification Simplify-main.cpp Simplify.h)

