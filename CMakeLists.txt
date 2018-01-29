cmake_minimum_required(VERSION 3.0)

# if using find_package, `#includes` need to be changed to `<catch/catch.hpp>`
# find_package(catch 2.2.1 REQUIRED)
add_subdirectory(catch)

add_executable(catch_usage catch_main.cpp)
target_link_libraries(catch_usage PRIVATE catch::catch)
