cmake_minimum_required(VERSION 3.15)

project(myvis LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(glfw3 REQUIRED)
find_package(GLEW REQUIRED)
find_package(OpenGL REQUIRED)

include(GNUInstallDirs)

add_subdirectory(src)
add_subdirectory(tests)