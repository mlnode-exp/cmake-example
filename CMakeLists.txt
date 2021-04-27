cmake_minimum_required(VERSION 3.10)

project(Timer)

set(CMAKE_EXPORT_COMPILE_COMMANDS 1)

include(/home/mlyko/sesja2021.1/github/professional/cpptest/integration/cmake/cpptest-project.cmake)

add_executable(timer
 clock.c
 driver.c
 timer.c
 stdinout.c)
