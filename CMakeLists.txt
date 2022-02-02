cmake_minimum_required(VERSION 3.0)

project(test1)

add_executable(test1 main.cpp)

install(TARGETS test1 RUNTIME DESTINATION bin)
