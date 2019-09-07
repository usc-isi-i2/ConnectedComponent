cmake_minimum_required(VERSION 2.8)
project(connectcomp)

set(CMAKE_CPP_FLAGS "${CMAKE_CPP_FLAGS} -Wall")

add_executable(connectcomp Graphstat.cpp Graphstat.h)

add_executable(randomwalk randomwalk.cpp randomwalk.h IOfunction.h memoryfunction.h function.h)

add_executable(TSV2wstandard tsv2weightstandard.cpp)
