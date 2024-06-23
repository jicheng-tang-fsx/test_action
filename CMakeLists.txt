cmake_minimum_required(VERSION 3.20)

project(mytest LANGUAGES CXX)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g -O3 -std=c++20 ")

add_executable(mytest ${CMAKE_SOURCE_DIR}/main.cpp)
