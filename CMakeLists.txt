cmake_minimum_required(VERSION 3.8)
project(my_fancy_project)

set(CMAKE_CXX_STANDARD 11)

file(GLOB my_files my_matrix_operation/*.cpp)

set(SOURCE_FILES main.cpp ${my_files})

include_directories(my_matrix_operation)

add_executable(my_fancy_project ${SOURCE_FILES} )