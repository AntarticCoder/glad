cmake_minimum_required(VERSION 3.0)

add_library(glad SHARED
    src/glad.c
)

target_include_directories(glad PUBLIC include)