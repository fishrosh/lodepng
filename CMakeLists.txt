cmake_minimum_required(VERSION 3.11)

project(lodepng VERSION 1.0.0)

add_library(lodepng STATIC lodepng.cpp
)

target_include_directories(lodepng INTERFACE
	${CMAKE_CURRENT_SOURCE_DIR}
)
