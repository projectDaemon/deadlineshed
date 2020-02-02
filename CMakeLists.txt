cmake_minimum_required(VERSION 2.8)

project(rt)

set(SOURCE main.cpp)

add_executable(rt ${SOURCE})
target_link_libraries(rt
    pthread
)