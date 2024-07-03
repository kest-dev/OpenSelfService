cmake_minimum_required(VERSION 3.27)
project(OpenSelfService)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(Log)

set(SOURCE_CODE main.cpp)

add_executable(OpenSelfService ${SOURCE_CODE})