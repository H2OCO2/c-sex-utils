cmake_minimum_required(VERSION 3.10)
project(c_utils C)

set(CMAKE_C_STANDARD 99)

add_executable(c_utils utils.c utils.h)

target_link_libraries(c_utils ssl)
target_link_libraries(c_utils crypto)