cmake_minimum_required(VERSION 3.2)

project(verdant VERSION 0.1)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY build)

add_executable(verdant src/main.c++)