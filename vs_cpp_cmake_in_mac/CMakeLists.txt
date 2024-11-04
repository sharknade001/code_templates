cmake_minimum_required(VERSION 3.5.0)
project(vs_cpp_cmake_in_mac VERSION 0.1.0 LANGUAGES C CXX)

add_executable(vs_cpp_cmake_in_mac main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
