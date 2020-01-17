cmake_minimum_required(VERSION 3.1)

project(kolokwium)

include_directories(${PROJECT_SOURCE_DIR})
add_executable(myProgram main.cpp address.cpp employee.cpp)
