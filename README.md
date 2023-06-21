The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written in C using the SDL2 library. Development was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

About SDL2


Simple DirectMedia Layer is a cross-platform development library that provides low-level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award-winning catalogue and many Humble Bundle games.

Installation

$ git clone https://github.com/Thebill1000/The_Maze.git

Usage

Execute ./maze or type make run

Use up and down arrow keys to move forward and backwards (keys w and s serve the same function)

Use the right and left arrow keys to turn the camera around (keys d and a serve the same function)

Compilation

$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;



Flowchart
![68747470733a2f2f692e696d6775722e636f6d2f74304d784e6e692e706e67](https://github.com/Thebill1000/The_Maze/assets/88892384/814359b0-d70d-41c3-bb17-bb4dd5a09388)

