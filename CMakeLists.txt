cmake_minimum_required(VERSION 3.0)
project(test_ga)

# Set C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -Wno-unused-variable")

# Add the main executable
add_executable(test_ga main.cpp)
