cmake_minimum_required(VERSION 3.4)
project(Lab3)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")

set(SOURCE_FILES main.c)
add_executable(Lab3 ${SOURCE_FILES})
