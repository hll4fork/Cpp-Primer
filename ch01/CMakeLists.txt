#
# author    : huang li long <huanglilongwk@outlook.com>
# time      : 2016/09/14
#

cmake_minimum_required(VERSION 3.2)
project(ch01 CXX)

# enable c++14
list(APPEND CMAKE_CXX_FLAGS "-std=c++14")

# include header file path 
include_directories(
    ${PROJECT_SOURCE_DIR}/../
)

# declare executable 
add_executable(ex1_1 ex1_1.cpp)
add_executable(ex1_10 ex1_10.cpp)
add_executable(ex1_11 ex1_11.cpp)
add_executable(ex1_16 ex1_16.cpp)
add_executable(ex1_20 ex1_20.cpp)
add_executable(ex1_21 ex1_21.cpp)
add_executable(ex1_22 ex1_22.cpp)
add_executable(ex1_23 ex1_23.cpp)
add_executable(ex1_9 ex1_9.cpp)

