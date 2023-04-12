cmake_minimum_required(VERSION 3.16.0)
project(counting CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_EXPORT_COMPILE_COMMANDS TRUE)
set(CMAKE_BUILD_TYPE=Debug)

add_executable(counting main.cpp)
