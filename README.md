# SPACESHIP GAME

- The python script makes use of Pygame, a popular GUI module, to develop an interactive multiplayer Spaceship Game.
- The 2 players compete to aim bullets at each other and the first player to lose their health, loses.

## Requirements:

All the packages essential for running the script can be installed as follows:

``` sh
$ pip install -r requirements.txt
```

# Gameplay Instructions:
1. To start playing the game, run `python main.py` in your terminal.

2. You will see two spaceships on the screen separated by one barrier in the middle  of the screen.

3. For player in the left side of the screen: 
    Use the W-A-S-D keys to move the spaceship up (W), down (S), left (A) or right (D).
    Use the left side CTRL key on your keyboard to shoot a bullet from the spaceship.

4. For player in the right side of the screen:
    Use the arrows keys to move the spaceship up (Up arrow), down (Down arrow), left  (Left arrow) or right (Right arrow).
    Use the right side CTRL key on your keyboard  to shoot a bullet from the spaceship.

5. If you manage to hit an opponent's spaceship with a bullet, it will reduce that player’s health by 1 point.

6. The first player to reduce the opponent's health to zero wins the game.