project(ConanGettingStarted)
cmake_minimum_required(VERSION 3.16)

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

enable_testing()
add_subdirectory(${PROJECT_SOURCE_DIR}/gtest)