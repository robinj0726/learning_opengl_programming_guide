add_executable(ch01.triangles triangles.cpp)
target_link_libraries(ch01.triangles PRIVATE opengl32.lib glew32s.lib glfw3.lib)