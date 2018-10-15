cmake_minimum_required(VERSION 3.1.0)         # CMake version check
project(builder)                              # Create project "builder"
set(CMAKE_CXX_STANDARD 17)                    # Enable c++17 standard

set(SOURCE_FILES builder.cpp)                 # Add builder.cpp file of project root directory as source file
add_executable(builder ${SOURCE_FILES})       # Add executable target with source files listed in SOURCE_FILES variable