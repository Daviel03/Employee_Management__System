cmake_minimum_required(VERSION 3.26)
project(Employee_Management__System)

set(CMAKE_CXX_STANDARD 17)

add_executable(Employee_Management__System main.cpp
        employee_information.cpp
        employee_information.h)
