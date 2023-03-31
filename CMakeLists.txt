cmake_minimum_required(VERSION 3.15)

project(awesome-solution LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
include_directories(/usr/include/yalantinglibs)
find_package(Threads REQUIRED)
add_subdirectory(helloworld)