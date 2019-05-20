cmake_minimum_required(VERSION 3.7)
project(tricorder)

set(CMAKE_CXX_STANDARD 11)

file(GLOB SOURCE_FILES "*.c" "*.h")

add_executable(tricorder ${SOURCE_FILES})

target_link_libraries(tricorder pthread)
