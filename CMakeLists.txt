cmake_minimum_required(VERSION 3.16)
project("Sample SDL project")
include_directories("/usr/include/SDL2")
add_executable(main main.c)
target_link_libraries(main m SDL2 SDL2_gfx)
#target_include_directories(main PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)