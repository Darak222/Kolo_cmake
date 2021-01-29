cmake_minimum_required(VERSION 3.10)
project(myProgram)
set(SOURCES ../src/address.cpp ../src/address.h ../src/employee.cpp ../src/employee.h ../src/main.cpp)
add_executable(myProgram ${SOURCES})

