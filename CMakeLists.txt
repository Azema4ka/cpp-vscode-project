cmake_minimum_required(VERSION 3.10)

project(ProjectCpp)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

file(GLOB_RECURSE SOURCES "${CMAKE_SOURCE_DIR}/src/*.cpp" "${CMAKE_SOURCE_DIR}/src/**/*.cpp")

add_executable(${PROJECT_NAME} ${SOURCES})