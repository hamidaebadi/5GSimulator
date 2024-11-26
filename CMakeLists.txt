#Min version required
cmake_minimum_required(VERSION 3.10)

#project name and version
project(5G_Simulator VERSION 0.0.1)

#Set c++ standard
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

#add include directory
include_directories(include)


# Find all .cpp files in the src directory and its subdirectories
file(GLOB_RECURSE SOURCES "src/*.cpp")

# Add the executable target
add_executable(5G_Simulator ${SOURCES})
