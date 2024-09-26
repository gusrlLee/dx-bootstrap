cmake_minimum_required(VERSION 3.5)
set(CMAKE_CXX_STANDARD 20)

add_subdirectory(vender)
project(dx-bootstrap)
add_executable(${PROJECT_NAME} main.cpp)
