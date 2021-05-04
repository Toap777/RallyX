cmake_minimum_required(VERSION 3.10)
project(RallyX)

set(CMAKE_CXX_STANDARD 20)

add_executable(RallyX main.cpp)
# TODO in cpp starter project verwenden Sie:
# target_link_libraries(demo PRIVATE project_warnings project_options X11 GL pthread png)
# statt:
target_link_libraries(RallyX PRIVATE X11 GL pthread png)

