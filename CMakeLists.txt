cmake_minimum_required(VERSION 3.6.1)
project (scratch)

include(CMakeToolsHelpers OPTIONAL)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_CXX_FLAGS "-std=c++14 -Wall -Wextra -Wpedantic -fcolor-diagnostics")

add_subdirectory(app)
add_subdirectory(test)
add_subdirectory(vendor/googletest/googletest)
