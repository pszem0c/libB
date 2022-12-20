cmake_minimum_required(VERSION 3.25)
project(libB)

set(CMAKE_CXX_STANDARD 20)

add_library(libB)

target_include_directories(libB PUBLIC include)

target_sources(libB PRIVATE src/libB.cpp)
