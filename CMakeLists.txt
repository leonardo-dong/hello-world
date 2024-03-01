project(hello-world C)
cmake_minimum_required(VERSION 2.6.3)

add_executable (hello-world main.c)

install(TARGETS hello-world DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)