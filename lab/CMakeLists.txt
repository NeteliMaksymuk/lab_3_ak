cmake_minimum_required(VERSION 3.16)

set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXXX_FLSGS "${CMAKE_CXX_FLAGS} -std=c++14")


project(lab)
add_executable(lab
	./main.cpp
)
