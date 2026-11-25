cmake_minimum_required(VERSION 3.10)

project(toygit)

add_executable(toygit main.cpp)
target_link_libraries(toygit PRIVATE components)
