cmake_minimum_required(VERSION 2.8.4)
project(libpit)

set(LIBPIT_SOURCE_FILES
    source/libpit.cpp)

add_library(pit STATIC ${LIBPIT_SOURCE_FILES})
