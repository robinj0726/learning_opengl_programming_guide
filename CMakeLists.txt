cmake_minimum_required(VERSION 3.10)
project(learning_opengl_programming_guide)

set(GLEW_INCLUDE_DIRS "C:/dev/External Libraries/glew-2.1.0-win32/glew-2.1.0/include")
set(GLEW_LIBRARIES_DIRS "C:/dev/External Libraries/glew-2.1.0-win32/glew-2.1.0/lib/Release/x64")

set(GLFW_INCLUDE_DIRS "C:/dev/External Libraries/glfw-3.3.8.bin.WIN64/include")
set(GLFW_LIBRARIES_DIRS "C:/dev/External Libraries/glfw-3.3.8.bin.WIN64/lib-vc2019/")

include_directories(${GLEW_INCLUDE_DIRS} ${GLFW_INCLUDE_DIRS})
link_directories(${GLEW_LIBRARIES_DIRS} ${GLFW_LIBRARIES_DIRS})

add_subdirectory(ch01)