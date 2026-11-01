cmake_minimum_required(VERSION 3.20)
project(ECL) # Explorer-cli
add_compile_options(-fdiagnostics-color=always)

set(CMAKE_CXX_STANDARD 23)

# ソースファイル
file(GLOB SOURCES src/*.cpp)

add_executable(${PROJECT_NAME} ${SOURCES})
