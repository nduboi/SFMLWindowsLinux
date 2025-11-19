cmake_minimum_required(VERSION 3.10)
project(SfmlOSXExample)
set(CMAKE_CXX_STANDARD 20)

add_subdirectory(SFML)
add_executable(SfmlOSXExample main.cpp)
target_link_libraries(SfmlOSXExample sfml-graphics sfml-window sfml-system)