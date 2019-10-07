cmake_minimum_required(VERSION 3.12)
project(lumaca_di_metallo)

set(CMAKE_CXX_STANDARD 14)

add_executable(lumaca_di_metallo main.cpp GameCharacter.cpp cmake-build-debug/Enemy.cpp cmake-build-debug/Enemy.h)