cmake_minimum_required(VERSION 3.22.1)

project(PortifolioWebsiteGenerator)

add_executable(${PROJECT_NAME} ../src/main.cpp)

install(TARGETS ${PROJECT_NAME} DESTINATION bin)