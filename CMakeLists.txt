cmake_minimum_required(VERSION 3.9)
project(parallel_programming_lab_1_histogram C)

set(CMAKE_C_STANDARD 11)

add_executable(parallel_programming_lab_1_histogram main.c)

set (CMAKE_C_FLAGS "${CMAKE_C_FLAGS} ${OpenMP_C_FLAGS}")
set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} ${OpenMP_CXX_FLAGS}")