cmake_minimum_required(VERSION 3.10) # Set the minimum version of CMake required. Adjust based on your CMake version.

# Set your project name and version
project(HelloWorld VERSION 1.0)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add an executable with the above sources
add_executable(hello_world src/main.cxx)
