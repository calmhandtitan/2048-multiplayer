2048-multiplayer
================

###Overview

Classic 2048 game, with the option to play multiplayer.

The multiplayer gaming is implemented using server-client socket programming.

Original Project: https://github.com/mevdschee/2048.c

###Dependencies

`GNU C++`

`Linux(Ubuntu) platform preferably 14.04`

###Compilation

To compile, run the following command on terminal

> $ g++ -o 2048.out 2048multiplayer.cpp -std=c++11

###Execution

To play the game in single user mode, simply run

> $ 2048.out

To play in multiplayer mode, first start the *server* using the command:

> $ 2048.out server

Now to play the game, start a client using the command

> $ 2048.out client

This command will ask for a *username*, and hence you are required to enter a valid username.

Next, it will ask the *Server IP/Host* to connect, and you are required to enter a host you want to connect to and start playing the game.
You can get to know your host by running command
> $ ifconfig

Alternatively, you can enter 127.0.0.1 to play on localhost.
