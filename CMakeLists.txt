cmake_minimum_required(VERSION 3.8)
project(my_fancy_project)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
main.cpp
    my_matrix_operation/my_matrix_operation.cpp
    my_matrix_operation/my_matrix_operation.h
    my_matrix_operation/asdf.cpp
    my_matrix_operation/asdf.h
)

include_directories(my_matrix_operation)

add_executable(my_fancy_project ${SOURCE_FILES} )