cmake_minimum_required(VERSION 3.28)
project(Stuff C)

set(CMAKE_C_STANDARD 99)

add_executable(Stuff main.c
        Utilities.c
        Utilities.h
        Singleplayergame.c
        Singleplayergame.h
        MultiplayerGame.c
        MultiplayerGame.h
        save.c
        save.h
)
