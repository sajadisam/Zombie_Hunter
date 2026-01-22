# Zombie Hunter

A 2D top-down shooter game with multiplayer support, built in C with the SDL2 library.

## Description

This is a classic 2D shooter where you control a player character and fight against waves of zombies. The game features multiplayer support, allowing multiple players to connect to a server and play together in the same world. The most important part of the project is the engine of which it is built with.

## Features

*   **Multiplayer:** Play with friends over the network. The game uses a client-server architecture to synchronize player and enemy states.
*   **2D Graphics:** The game uses sprites for the player, enemies, and projectiles, and a tile-based world renderer.
*   **Collision Detection:** The game implements collision detection between players, enemies, and projectiles.
*   **Animations:** The player and enemies have simple animations.
*   **UI:** The game has a simple UI, including a main menu, health display, and a game-over screen.

## Getting Started

### Prerequisites

*   A C compiler (like GCC)
*   The SDL2 library
*   The SDL2_image library
*   The SDL2_ttf library
*   The SDL2_net library

### Building and Running

The project is split into a `client` and a `server`. You will need to build and run both to play the game.

#### Server

1.  Navigate to the `server` directory:
    ```bash
    cd server
    ```
2.  Build the server:
    ```bash
    make
    ```
3.  Run the server:
    ```bash
    ./server
    ```

#### Client

1.  In a new terminal, navigate to the `client` directory:
    ```bash
    cd client
    ```
2.  Build the client:
    ```bash
    make
    ```
3.  Run the client:
    ```bash
    ./client
    ```

## Technologies Used

*   **Language:** C
*   **Graphics and Networking:** SDL2, SDL2_image, SDL2_ttf, SDL2_net
*   **Build System:** Make
