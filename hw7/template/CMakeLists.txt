cmake_minimum_required(VERSION 2.6)
PROJECT(hw7)

set(CMAKE_CXX_FLAGS -std=c++11)

FIND_PACKAGE( Eigen REQUIRED )
INCLUDE_DIRECTORIES(${EIGEN_INCLUDE_DIRS})

SUBDIRS( src test )