cmake_minimum_required(VERSION 3.3)
project(apue)
include_directories(include)
add_subdirectory(signals)
add_subdirectory(threads)
add_subdirectory(threadctl)
add_subdirectory(daemons)
add_subdirectory(advio)
add_subdirectory(ipc1)