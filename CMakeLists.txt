# cmake_minimum_required(VERSION <specify CMake version here>)
project(tinyhttpd)

set(CMAKE_C_STANDARD 99)
set(CMAKE_LEGACY_CYGWIN_WIN32 0)

add_executable(untitled httpd.c)