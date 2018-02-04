cmake_minimum_required(VERSION 3.0)

#find_package(Catch2 2.1.0 REQUIRED)
add_subdirectory(catch)

add_executable(catch_usage catch_main.cpp)
target_link_libraries(catch_usage PRIVATE Catch2::Catch)
