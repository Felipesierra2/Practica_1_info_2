cmake_minimum_required(VERSION 3.16)

project(Practica_1_info_ll LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Practica_1_info_ll main.cpp)

include(GNUInstallDirs)
install(TARGETS Practica_1_info_ll
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
