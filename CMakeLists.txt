cmake_minimum_required(VERSION 3.28.3)

project(libcanard)

add_library(libcanard STATIC
    "libcanard/canard.c"
)

target_include_directories(libcanard
    PUBLIC
        "libcanard"
)
