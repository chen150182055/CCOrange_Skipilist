cmake_minimum_required(VERSION 3.22)
project(CCOrange_Skipilist)

set(CMAKE_CXX_STANDARD 14)

find_package(Threads REQUIRED)
add_executable(CCOrange_Skipilist main.cpp)
target_link_libraries(CCOrange_Skipilist
        pthread
        )
