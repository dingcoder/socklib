cmake_minimum_required(VERSION 3.8)
project(socklib)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES socklib.c)
add_executable(socklib ${SOURCE_FILES})