cmake_minimum_required(VERSION 3.10)
project(CyberCommander)

# Look for SDL2 and SDL2_mixer
find_package(SDL2 REQUIRED)
find_package(SDL2_mixer REQUIRED)

add_executable(CyberCommander main.cpp)

# Link the libraries
target_link_libraries(CyberCommander SDL2::SDL2 SDL2_mixer::SDL2_mixer)

 
