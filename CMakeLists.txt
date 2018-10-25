cmake_minimum_required(VERSION 2.8.3)
set(PROJECT_NAME JPL_SE3_Pose)
project(${PROJECT_NAME})

set(CMAKE_CXX_FLAGS "-std=c++11 -O3")


find_package(Eigen3  REQUIRED)
include_directories(include 
        ${EIGEN3_INCLUDE_DIR})

# test
#add_executable(test test/test.cpp)







