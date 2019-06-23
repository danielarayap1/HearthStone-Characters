# Project- HearthStone Characters

HearthStone is a popular online card game. In this project I used the main characters from this game, simulating some advantages and weaknesses of some characters above others.

The main Cards are:
* Assassin
* Druid
* Healer
* Hunter
* Knight
* Mage
* Paladin
* Shaman
* Warlock

This project applies *Double Dispatch* and the concepts of Inheritance in Java to implement the attacks and damage calculation for the cards.

This damage calculation depends on what cards are fighting. The relation goes like this:
* Assassin receives double damage from Warlock attacks and raises his attack by half of the Druid's attack receiving no damage from him.
* Druid raises a card's attack using all of his attack and damages that card by half of Druid's attack. Druid receives double effects from Shaman and Paladin's effects.
* Healer restores damage from a card (can't resurrect it), using 1/2 of his attack. Receives double attack from Assassin and double effects from Paladin's attack.
* Paladin raises the attack and restores damage from a card using 1/3 of Paladin's attack.
* Shaman decreases attack and damage a card using 1/3 of Shaman's attack.
