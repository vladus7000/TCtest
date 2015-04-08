cmake_minimum_required(VERSION 2.8)

project(gles20_directed)

set (APP gles20_directed)

set ( SRCS 
	main.cpp
)
add_executable(${APP} ${SRCS})