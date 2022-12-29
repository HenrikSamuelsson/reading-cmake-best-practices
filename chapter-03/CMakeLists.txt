cmake_minimum_required(VERSION 3.21)

project (
    hello_world_standalone
    VERSION 1.0
    DESCRIPTION "A simple C++ project"
    LANGUAGES CXX
)

add_executable(hello_world_standalone)
target_sources(hello_world_standalone PRIVATE source/main.cpp)
