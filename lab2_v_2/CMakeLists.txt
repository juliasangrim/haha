cmake_minimum_required(VERSION 3.17)
project(lab2_2 C)

set(CMAKE_C_STANDARD 99)

add_executable(lab2_2 main.c)
target_link_libraries(lab2_2 -lm -fopenmp)