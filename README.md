# Game Title: Treasure Hunt

# Import required modules
import random

# Define game variables
player_name = input("Enter your name: ")
player_health = 100
player_score = 0

# Game loop
while player_health > 0:
    # Display player status
    print(f"\n{player_name}'s Status:")
    print(f"Health: {player_health}")
    print(f"Score: {player_score}")

    # Present player with choices
    print("\nYou are in a dark room. You see two doors:")
    print("1. Door 1 (looks spooky)")
    print("2. Door 2 (looks normal)")

    # Get player input
    choice = input("Which door do you choose? (1/2): ")

    # Handle player choice
    if choice == "1":
        # Spooky door
        
