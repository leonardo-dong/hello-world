project(hello-yocto C)
cmake_minimum_required(VERSION 2.6.3)

add_executable (hello-yocto main.c)

install(TARGETS hello-yocto DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)