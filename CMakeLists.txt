cmake_minimum_required(VERSION 3.28)
project(conan_16497_reproduction)

set(CMAKE_CXX_STANDARD 23)

find_package(SFML REQUIRED)

add_executable(conan_16497_reproduction src/main.cpp)
target_link_libraries(conan_16497_reproduction PUBLIC sfml::sfml)