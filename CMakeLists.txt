cmake_minimum_required (VERSION 3.10.2)
project (ADS-8)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3 -g")


set(tool_dest "bin")
set(lib_dest "lib")
set(include_dest "include/")

set(SOURCES
    src/main.cpp
    src/alg.cpp
)

add_subdirectory(src)
add_subdirectory(test)
