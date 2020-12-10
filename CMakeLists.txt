cmake_minimum_required(VERSION 2.8)

project(ak2_lab_2)

add_library(calculator
    calculator.h
    calculator.cpp
)

add_executable(ak2_lab_2
  main.cpp
)

target_link_libraries(ak2_lab_2 calculator)
