cmake_minimum_required(VERSION 3.16)

project(frieren_rpg VERSION 0.1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Set output directories
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

# Include directories
include_directories(include)

# Collect all .cpp files in src/ and subdirectories
file(GLOB_RECURSE SOURCES CONFIGURE_DEPENDS src/*.cpp)

# Add executable
add_executable(frieren_rpg ${SOURCES})

# Example: Add assets directory to the runtime directory (optional)
# file(COPY assets/ DESTINATION ${CMAKE_RUNTIME_OUTPUT_DIRECTORY}/assets)

# Enable testing (if you want to add tests later)
enable_testing()
