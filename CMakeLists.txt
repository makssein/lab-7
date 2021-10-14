cmake_minimum_required(VERSION 3.20)
project(lab_7)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(lab_7
        functions.cpp
        functions.hpp
        main.cpp)
