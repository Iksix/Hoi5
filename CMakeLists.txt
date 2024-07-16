cmake_minimum_required(VERSION 3.30 FATAL_ERROR)

set(PORJECT_NAME Hoi5pp)

project(${PORJECT_NAME})

add_executable(${PORJECT_NAME} src/main.cpp)

add_subdirectory(external/glfw)
target_link_libraries(${PORJECT_NAME} glfw)