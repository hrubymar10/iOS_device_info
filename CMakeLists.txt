project(iOS_device_info)
cmake_minimum_required(VERSION 3.0)
set (CMAKE_CXX_STANDARD 14)

include_directories(${Boost_INCLUDE_DIRS} SYSTEM)

set(SOURCE_FILES
		src/iOS_device_info.cpp
		src/iOS_device_info.hpp
		)

add_library(iOS_device_info ${SOURCE_FILES})
