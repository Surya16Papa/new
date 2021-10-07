cmake_minimum_required(VERSION 3.16.3)
project(hello)

include_directories(include)

#set(SOURCES src/main.c src/hello.c src/add.c src/sub.c)
file(GLOB SOURCES "src/*.c")

add_executable(hello ${SOURCES})

