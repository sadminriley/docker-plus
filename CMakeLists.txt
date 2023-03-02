cmake_minimum_required(VERSION 3.24)

project(docker-plus)

set(EXTERNAL_LIB_HEADERS lib/docker)

set(CMAKE_CXX_STANDARD 14)

include_directories(lib)

add_subdirectory(lib)
