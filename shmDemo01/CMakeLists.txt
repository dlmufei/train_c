cmake_minimum_required(VERSION 3.7)
project(shmDemo01)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES_1 src/main_shm01.cpp)
set(SOURCE_FILES_2 src/main_shm02.cpp)
set(SOURCE_FILES_3 src/main_shm03.cpp)

add_executable(shmDemo01 ${SOURCE_FILES_1})
add_executable(shmDemo02 ${SOURCE_FILES_2})
add_executable(shmDemo03 ${SOURCE_FILES_3})