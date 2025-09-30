# CMakeLists for Payton's repository

# Set up
cmake_minimum_required (VERSION 3.5)
set(CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake_modules")
find_package(ROOT REQUIRED)

# Project name
project (Payton_Repo)

include_directories(${CMAKE_SOURCE_DIR}/include ${ROOT_INCLUDE_DIR})

# Add a subdirectory for examples
add_subdirectory(examples)
