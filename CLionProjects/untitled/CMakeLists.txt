cmake_minimum_required(VERSION 3.28)
project(untitled)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled main.cpp
        bankSystem.cpp
        bankSystem.h
        bussinesLogic.cpp
        bussinesLogic.h)
