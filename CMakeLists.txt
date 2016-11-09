cmake_minimum_required(VERSION 3.6)
project(Shapes_v_5)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES Shapes.6.cpp pShapes.cpp pShapes.h)
add_executable(Shapes_v_5 ${SOURCE_FILES})