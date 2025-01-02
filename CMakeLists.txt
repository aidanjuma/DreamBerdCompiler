cmake_minimum_required(VERSION 3.30)
project(DreamBerdCompiler)

set(CMAKE_CXX_STANDARD 20)

add_executable(DreamBerdCompiler src/main.cpp
        src/lexer.cpp
        include/lexer.h
        src/parser.cpp
        include/parser.h
        src/codegen.cpp
        include/codegen.h)
