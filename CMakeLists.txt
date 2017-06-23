cmake_minimum_required(VERSION 3.1)

project(Eris)

file(GLOB ERIS_SOURCES src/*.c)

add_library(Eris ${ERIS_SOURCES})
target_include_directories(Eris PUBLIC src)