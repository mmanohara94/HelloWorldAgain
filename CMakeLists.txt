cmake_minimum_required(VERSION 3.8)
project(my_fancy_project)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(my_fancy_project ${SOURCE_FILES})