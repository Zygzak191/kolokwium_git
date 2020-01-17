cmake_minimum_required(VERSION 3.1)
project(TestLibrary)

set(CMAKE_INSTALL_PREFIX ./)
include_directories(include)
add_library(testStudent SHARED src/Student.cpp)
add_executable(libtest src/libtest.cpp)

target_link_libraries(libtest testStudent)
