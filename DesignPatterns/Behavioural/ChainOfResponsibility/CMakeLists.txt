cmake_minimum_required(VERSION 3.5)

project(ChainOfResponsibility LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(ChainOfResponsibility main.cpp)

install(TARGETS ChainOfResponsibility
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
