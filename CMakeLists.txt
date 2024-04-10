cmake_minimum_required(VERSION 3.12)

project(DearImui)

add_library(imgui STATIC
    imgui.cpp
    imgui_draw.cpp
    imgui_demo.cpp
)

target_include_directories(imgui PUBLIC .)
