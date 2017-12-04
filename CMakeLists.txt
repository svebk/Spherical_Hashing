cmake_minimum_required(VERSION 3.0)

project(sph)

set(SRCS
    Src_CPP/BinaryHash.cpp
    Src_CPP/Common.cpp
    Src_CPP/Stopwatch.cpp
    Src_CPP/Main.cpp
    )
    
set(HEADERS
    Src_CPP/BinaryHash.h
    Src_CPP/Common.h
    Src_CPP/Evaluation.h
    Src_CPP/Parameters.h
    Src_CPP/Points.h
    Src_CPP/Stopwatch.hpp
    )

add_executable(sph ${SRCS} ${HEADERS})
