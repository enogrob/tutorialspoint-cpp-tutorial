cmake_minimum_required(VERSION 3.4)
project(tutorialspoint_cpp_tutorial)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES code/main.cpp code/variable_types.cpp code/static_storage.cpp.cpp)
add_executable(tutorialspoint_cpp_tutorial ${SOURCE_FILES})
add_executable(main code/main.cpp)
add_executable(sizeof code/sizeof.cpp)
add_executable(variable_types code/variable_types.cpp)
add_executable(static_storage.cpp code/static_storage.cpp.cpp)