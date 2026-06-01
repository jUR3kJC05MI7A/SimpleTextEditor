cmake_minimum_required(VERSION 3.25)

project(kilo)

add_executable(kilo)

target_sources(kilo
	PRIVATE
	../kilo/src/main.cpp
	../kilo/src/func.cpp	
	
	PUBLIC
	FILE_SET HEADERS
	BASE_DIRS
	 include
	FILES
	 ../kilo/include/headers.hpp
)
