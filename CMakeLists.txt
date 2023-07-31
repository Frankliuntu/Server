cmake_minimum_required(VERSION 3.25)
project(Server)

set(CMAKE_CXX_STANDARD 17)
AUX_SOURCE_DIRECTORY(. SRC_List)
add_executable(Server ${SRC_List})
