cmake_minimum_required(VERSION 3.0)

project(test LANGUAGES CXX)

find_package(autodiff REQUIRED)

add_executable(test main.cpp)

target_link_libraries(test autodiff::autodiff)
