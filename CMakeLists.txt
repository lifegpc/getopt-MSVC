cmake_minimum_required(VERSION 3.0)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})
add_library(getopt STATIC getopt.c getopt1.c getopt_core.h getopt_ext.h getopt_int.h getopt.h)
