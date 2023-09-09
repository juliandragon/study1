cmake_minimum_required( VERSION 3.22)

project(app)
aux_source_directory(. DIR_SRCS)
set(CMAKE_CXX_STANDARD 11)

add_executable(app main.cpp)