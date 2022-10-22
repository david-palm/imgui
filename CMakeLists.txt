cmake_minimum_required(VERSION 3.22)
project(uml-creator)

add_library(imgui imgui.cpp)

target_include_directories(imgui PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})