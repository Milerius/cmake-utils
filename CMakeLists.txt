cmake_minimum_required(VERSION 3.0)

project(ProjectName)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} ${CMAKE_SOURCE_DIR}/cmake)
include(${CMAKE_MODULE_PATH}/include.cmake)
PROJECT_FOLDER(${PROJECT_NAME})
