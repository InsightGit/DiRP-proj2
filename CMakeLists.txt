cmake_minimum_required(VERSION 3.24)
project(proj2)

set(CMAKE_CXX_STANDARD 17)

add_executable(proj2 libsrc/glad.c src/materials.cpp)

target_include_directories(proj2 PUBLIC include/)
target_link_libraries(proj2 PUBLIC glfw)