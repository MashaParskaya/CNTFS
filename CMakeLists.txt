cmake_minimum_required(VERSION 2.8)

project(CNTFS)

set(CNTFS_src main.cpp CNTFS.cpp autotest.cpp)
set(CNTFS_hdr CNTFS.hpp autotest.hpp)

add_executable(${PROJECT_NAME} ${CNTFS_src} ${CNTFS_hdr})

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14 /std:c++14")
