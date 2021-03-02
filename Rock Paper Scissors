"""
Rock Paper Scissors
----------------------------------------
Basic rock paper scissors game played between a player
and an automated system.
"""
import random
import os
import re
os.system('cls' if os.name == 'nt' else 'clear')
while True:
    print("\n")
    print("Rock, Paper, Scissors - Start!")
    player1Choice = input("Choose your weapon [R]ock], [P]aper, or [S]cissors: ")
    if not re.match("[SsRrPp]", player1Choice):
        print("Please choose a letter: ")
        print("[R]ock, [S]cissors or [P]aper.")
        continue
    # Echo player1's choice
    print("You chose: " + player1Choice)
    choices = ['R', 'P', 'S']
    player2Choice = random.choice(choices)
    print("I chose: " + player2Choice)
    if player2Choice == str.upper(player1Choice):
        print("Tie!")
    # if player2Choice == str("R") and str.upper(player1Choice) == "P"
    elif player2Choice == 'R' and player1Choice.upper() == 'S':
        print("Scissors beats rock, I win!")
        continue
    elif player2Choice == 'S' and player1Choice.upper() == 'P':
        print("Scissors beats paper! I win!")
        continue
    elif player2Choice == 'P' and player1Choice.upper() == 'R':
        print("Paper beat rock, I win!")
        continue
    else:
        print("You win!")
