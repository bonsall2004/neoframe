cmake_minimum_required(VERSION 3.27)
project(NeoFrame)

include_directories(dependencies/includes)

set(CMAKE_CXX_STANDARD 17)

add_executable(NeoFrame main.cpp)