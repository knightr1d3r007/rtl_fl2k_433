cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(rtl_fl2k_433 VERSION 1.0)
add_executable(rtl_fl2k_433 rtl_fl2k_433.cpp) 
target_include_directories(rtl_fl2k_433 PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
file(GLOB_RECURSE SRC_FILES src/*.cpp)
