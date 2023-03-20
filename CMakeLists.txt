cmake_minimum_required(VERSION 3.16)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

project(main)

add_executable(main test.cpp)

install(TARGETS main)

enable_testing()
add_test(NAME main COMMAND main)
