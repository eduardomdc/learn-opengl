cmake_minimum_required(VERSION 3.0)
project(Glad)
add_library(glad /usr/include/glad/glad.h glad.c)
target_include_directories(glad PUBLIC /usr/include/)
