# Two-Player-Battle
Introduction

This is a simple Python text-based fighting game that allows two players to fight against each other.
The player's status, such as their health points, energy points, and the number of hits they have taken, are displayed throughout the game.

Gameplay

The game starts with two players, Ahmet and Mehmet, who are facing each other. The players can choose to attack, run away, or quit the game. The attack outcome is determined by a random number generator.

The players can attack each other until one of them runs out of health points. The energy points decrease with each hit, and the health points decrease when the player takes five hits. If a player's health points reach 0, the game is over and the opponent wins.

Classes and Methods

The game is built using the class Oyuncu, which has the following attributes and methods:

isim: the name of the player
darbe: the number of hits the player has taken
can: the player's health points
enerji: the player's energy points
mevcut_durumu_görüntüle: displays the player's current status
saldır: the player attacks the opponent
saldırı_sonucunu_hesapla: calculates the outcome of the attack
kaç: the player runs away
darbele: the player takes a hit from the opponent
oyundan_çık: the player quits the game

Requirements

This game requires the time and random modules.

Usage

To start the game, simply run the script in your terminal. Follow the prompt to choose your action (attack, run away, or quit the game). The outcome of the attack and the players' status will be displayed after each action.

Conclusion

This game provides a simple and fun way to experience a text-based fighting game. You can modify and extend the code to add new features or improve the gameplay. Have fun playing!
