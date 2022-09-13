cmake_minimum_required(VERSION 3.5)

project(Adapter LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Adapter main.cpp)

install(TARGETS Adapter
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
