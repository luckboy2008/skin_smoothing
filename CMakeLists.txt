CMAKE_MINIMUM_REQUIRED(VERSION 2.4)
project(skin_smoothing)
SET(CMAKE_BUILD_TYPE "Release")
add_executable(skin_smoothing skin_smoothing.c)
target_link_libraries(skin_smoothing -lm)