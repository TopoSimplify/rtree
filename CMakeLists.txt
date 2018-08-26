cmake_minimum_required(VERSION 3.0)
project(rtree)
set(CMAKE_CXX_STANDARD 17)
add_subdirectory(lib)

add_executable(rtree main.cpp)
target_link_libraries(rtree librtree)