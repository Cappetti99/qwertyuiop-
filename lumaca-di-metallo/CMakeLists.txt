cmake_minimum_required(VERSION 3.12)
project(lumaca_di_metallo)

set(CMAKE_CXX_STANDARD 14)

add_executable(lumaca_di_metallo main.cpp GameCharacter.cpp Enemy.cpp Champ.cpp Champ.h Item.cpp Item.h Weapon.cpp Weapon.h Map.cpp Map.h)