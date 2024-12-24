cmake_minimum_required(VERSION 3.14)
project(xrt)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_BUILD_TYPE debug)
set (CMAKE_CXX_STANDARD 11)

add_subdirectory(src)
add_subdirectory(tests)
