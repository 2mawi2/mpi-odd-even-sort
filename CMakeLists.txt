cmake_minimum_required(VERSION 3.9)
project(Odd-Even-Sort-mit-MPI)

set(CMAKE_CXX_STANDARD 11)

add_executable(Odd-Even-Sort-mit-MPI implementation/c++/OddEvenSort.cpp implementation/c++/ReadBinaryFileIntoArray_Example.cpp implementation/c++/ReadBinaryFileIntoVector_Example.cpp implementation/c++/RandomNumberGenerator.cpp)