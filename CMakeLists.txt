cmake_minimum_required(VERSION 3.3)
project(mtftable)

set(CMAKE_C_FLAGS "-std=c99")


set(SOURCE_FILES dlist.c dlist.h table.c table.h tabletest.c)
add_executable(tabletest ${SOURCE_FILES} tabletest.c)