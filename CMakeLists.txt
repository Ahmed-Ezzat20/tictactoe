cmake_minimum_required(VERSION 3.25)
project(Tic_Tac_Toe_Game_main)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Tic_Tac_Toe_Game_main
        main.cpp
        TicTacToe.cpp
        TicTacToe.h)
