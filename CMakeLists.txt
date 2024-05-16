cmake_minimum_required(VERSION 3.28)
project(textschange)

set(CMAKE_CXX_STANDARD 17)

add_executable(textschange main.cpp
        text.cpp
        text.h)
