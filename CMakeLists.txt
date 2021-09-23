cmake_minimum_required(VERSION 3.20)
project(TD_3)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(grading)
include_directories(gradinglib)

add_executable(TD_3
        grading/grading.cpp
        grading/grading.hpp
        grading/memplumber-internals.hpp
        grading/memplumber.cpp
        grading/memplumber.hpp
        gradinglib/gradinglib.cpp
        gradinglib/gradinglib.hpp
        main.cpp
        support.cpp
        support.hpp
        td3.cpp
        td3.hpp)
