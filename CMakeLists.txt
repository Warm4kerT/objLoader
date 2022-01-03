cmake_minimum_required(VERSION 3.21)
project(objLoader)

set(CMAKE_CXX_STANDARD 14)

add_executable(objLoader main.cpp)
target_link_libraries(objLoader glfw -lglut -lGL -lGLU GLEW -ldl)