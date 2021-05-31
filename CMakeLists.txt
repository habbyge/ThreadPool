cmake_minimum_required(VERSION 3.17)
project(threadpool)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "-std=c++11")

add_executable(example.cpp)

include_directories(thread_pool.h)
