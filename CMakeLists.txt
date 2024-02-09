project(YourProject)

add_subdirectory(external/glfw)
include_directories(external/glfw/include)

add_executable(YourExecutable src/main.c)
target_link_libraries(YourExecutable glfw)
