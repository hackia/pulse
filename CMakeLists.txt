cmake_minimum_required(VERSION 4.0)
project(pulse)

set(CMAKE_CXX_STANDARD 26)
add_executable(pulse main.cpp)
install(TARGETS pulse DESTINATION bin)
