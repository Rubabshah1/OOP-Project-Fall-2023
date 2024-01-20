# OOP-Project-Flappy Bird

Our game is inspired by the classic Flappy Bird game, with a few additional features such as keeping track of lives lost, and gained (by collecting hearts), increasing the score by collection of coins, and also allowing the player to choose the bird they want to play the game with at the start screen.. This game makes use of SDL libraries for the GUI and takes in to account certain OOP concepts like abstraction, operator overloading, runtime polymorphism, inheritance, etc.

Project created by: Syeda Samah Daniyal, Rubab Shah, Shifa Shah

How to Compile: THE FILES ABOVE ARE MODIFIED TO RUN ON WINDOWS. YOU MAY NEED TO MAKE THE FOLLOWING CHANGES

Windows: Open this folder in VSCode and then in the terminal copy the commands for compiling and running the game.

Compiling: g++ *.cpp -IC:\mingw_dev_lib\include\SDL2 -LC:\mingw_dev_lib\lib -w -lmingw32 -lSDL2main -lSDL2 -lSDL2_image -lSDL2_mixer

Running the game: .\a.exe

Mac: Open this folder in VSCode, make the following changes in the files and then in the terminal copy the command for compiling and running the game.

Change #include<SDL.h> to #include<SDL2.h> Change #include<SDL_image.h> to #include<SDL2/SDL_image.h> Change #include<SDL_mixer.h> to #include<SDL2/SDL_mixer.h>

Compiling: g++ *.cpp -std=c++11 -lSDL2 -lSDL2_image -lSDL2_mixer

Running the game: ./a.out
![image](https://github.com/Rubabshah1/OOP-Project-Fall-2023/assets/122277869/1622f847-06da-46db-88eb-cb4254790a51)
![image](https://github.com/Rubabshah1/OOP-Project-Fall-2023/assets/122277869/77c49c14-997f-468d-a625-9de1a7e6a261)

