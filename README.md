# Magical-Arena

## Description

"Design a Magical Arena. Every Player is defined by a “health” attribute, “strength” attribute and an “attack” attribute - all positive integers. The player dies if his health attribute touches 0.
Any two player can fight a match in the arena. Players attack in turns. Attacking player rolls the attacking dice and the defending player rolls the defending dice. The “attack” value multiplied by the outcome of the attacking dice roll is the damage created by the attacker. The defender “strength” value, multiplied by the outcome of the defending dice is the damage defended by the defender. Whatever damage created by attacker which is in excess of the damage defended by the defender will reduce the “health” of the defender. Game ends when any players health reaches 0

1. Player with lower health attacks first at the start of a match.

2. Assume two players . Player A 50 health 5 strength 10 attack Player B 100 health 10 stregnth and 5 attack . Attacking die and Defending die are both 6 sided die with values ranging from 1- 6

3. Player A attacks and rolls die. Die roll : 5 . Player B defends and rolls die. Die roll 2

4. Attack damage is 5 _ 10 = 50 ; Defending strength = 10 _ 2 = 20 ; Player B health reduced by 30 to 70

5. Player B attacks and rolls die. Die roll : 4. Player A defends and rolls die. Die Roll 3

6. Attack damage is 4 _ 5 = 20 ; Defending strength = 5 _ 3 = 15 ; Player A health reduced by 5 to 45

And so on

## Getting Started

1. Download the zip file from the repository.
2. Extract the contents of the zip file to a directory on your local machine.
3. Make sure you have Java installed on your system.
4. Open a terminal or command prompt.
5. Navigate to the directory where you extracted the zip file.

## Compile and run the source code

1.  Compile the Java files using a Java compiler using command <br>
    `javac Main.java`
1.  Run the game using command <br>
    `java Main`

## How to play

1.  Enter the attributes for Player A when prompted (health, strength, attack).
2.  Enter the attributes for Player B when prompted (health, strength, attack).
3.  The game will simulate the battle between the two players, with Player having less health attacking first.
4.  The attacker's attack value, multiplied by the attacking dice roll, determines the damage inflicted, while the defender's strength value, multiplied by the defending dice roll, determines the damage defended.
5.  Any excess damage from the attacker reduces the defender's health.
6.  The game continues with players exchanging attacker and defender roles until one player's health reaches zero, indicating the end of the match.
7.  The game announces the winner based on which player's health reaches zero first.
