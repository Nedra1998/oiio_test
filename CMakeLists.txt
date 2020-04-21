cmake_minimum_required(VERSION 3.11)
project(oiio_test)

add_subdirectory(oiio)
add_executable(test main.cpp)
target_link_libraries(test PUBLIC OpenImageIO)
