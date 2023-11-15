cmake_minimum_required(VERSION 3.12)

project(imguibuild CXX C)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_EXTENSIONS NO)
set(CMAKE_CXX_STANDARD_REQUIRED YES)

add_library(imguibuild "src/imguiwrapper.cpp")
target_include_directories(imguibuild PUBLIC "../imgui")