cmake_minimum_required(VERSION 3.5)

project(PimplTrial LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(PimplTrial main.cpp)

install(TARGETS PimplTrial
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
