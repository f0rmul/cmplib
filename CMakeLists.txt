cmake_minimum_required(VERSION 3.5 FATAL_ERROR)
project(cmplib LANGUAGES CXX)

add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(${PROJECT_NAME} INTERFACE ${CMAKE_CURRENT_LIST_DIR})