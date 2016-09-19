cmake_minimum_required(VERSION 3.4)
project(fastText_master_new)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    src/args.cc
    src/args.h
    src/dictionary.cc
    src/dictionary.h
    src/fasttext.cc
    src/fasttext.h
    src/matrix.cc
    src/matrix.h
    src/model.cc
    src/model.h
    src/real.h
    src/utils.cc
    src/utils.h
    src/vector.cc
    src/vector.h)

add_executable(fastText_master_new ${SOURCE_FILES})