cmake_minimum_required(VERSION 3.0)
project(starter_project)

set(CMAKE_CXX_STANDARD 11)

include_directories(${PROJECT_SOURCE_DIR}/include)

aux_source_directory(${PROJECT_SOURCE_DIR}/src SRCS)

add_executable(starter_project ${SRCS})
