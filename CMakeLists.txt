cmake_minimum_required(VERSION 2.8.9)
set(CMAKE_CXX_COMPILER "g++")
set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -lstdc++ -std=gnu++11")
project (hello)
add_executable(hello main.cpp)