cmake_minimum_required(VERSION 3.0.2)

project(http-parser-test C CXX)

include(CheckCXXCompilerFlag)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -g -O0 -Wall -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")

include_directories(.)

add_subdirectory(mytest)
