cmake_minimum_required(VERSION 3.10)

# Set the project name
project(ShinyAsteroids)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(ShinyAsteroids
    src/main.cpp
    # Add other source files here
)

# Include directories
target_include_directories(ShinyAsteroids PUBLIC
    ${PROJECT_SOURCE_DIR}/include
)
