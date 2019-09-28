cmake_minimum_required(VERSION 3.14)
project(php_src)

set(CMAKE_CXX_STANDARD 14)

include_directories(${PROJECT_SOURCE_DIR})

add_custom_target(php_src COMMAND make)