cmake_minimum_required(VERSION 3.13)

project(FREngine)

set(CMAKE_CXX_STANDARD 17)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_executable(FREngine main.cpp)