# Specify the minimum required version of CMake
cmake_minimum_required(VERSION 3.10)

# Project name and version
project(MyProject VERSION 1.0)

# Specify C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable target
add_executable(MyProject main.cpp)

# Optionally, you can specify installation paths
install(TARGETS MyProject DESTINATION bin)
