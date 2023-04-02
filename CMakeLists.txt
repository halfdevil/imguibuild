cmake_minimum_required(VERSION 3.12)

project(imguibuild CXX C)

add_library(imguibuild "src/imguiwrapper.cpp")
target_include_directories(imguibuild PUBLIC "../imgui")