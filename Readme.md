![maze1notex](https://github.com/Daveroyz/3D_Maze/assets/124052586/f51e97c5-5e60-4e0a-aa37-48ee9632a17e)


The Maze
The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

About SDL2
Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

Instalation
Install SDL2 and SDL2_Image on ubuntu operating system
git clone the game repository.
Run the following command to compile to source code "gcc -O2 -g -Wall -Werror -Wextra -pedantic -Isrc/headers *.c -lSDL2 -lSDL2_image -lm -o maze sdl2-config --cflags --libs" in the 3D_Maze repo.
After complete compiling run this command ./maze to start the game.

Usage
Execute ./maze or type make run

Use w and s keys to move forward and backward 
Use a and d keys to turn the camera arround.

Compilation
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;

