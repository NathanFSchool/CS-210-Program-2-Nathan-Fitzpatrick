cmake_minimum_required(VERSION 4.3)
project(Program2)

set(CMAKE_CXX_STANDARD 20)

add_executable(Program2
        request.h
        loadbalancer.h
        webserver.cpp
        webserver.h
        loadbalancer.cpp
        p2.cpp)
