cmake_minimum_required(VERSION 3.5)

project(Factory LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Factory main.cpp)

install(TARGETS Factory
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
