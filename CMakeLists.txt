cmake_minimum_required(VERSION 3.16)
project(Handwritten_Digit_Recognition-cpp)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(HDR-cpp
        src/data_loader.h
        src/neural_network.h
        src/recognition.cpp
        src/timer.h)
