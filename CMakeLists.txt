cmake_minimum_required(VERSION 3.10)

project(CPPCPP)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_compile_options(-Wextra -pedantic -O0)

add_executable(main main.cpp)