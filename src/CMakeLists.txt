cmake_minimum_required(VERSION 3.10)
add_subdirectory(lib)
add_executable(calculator main.c)
target_link_libraries(calculator lib)
