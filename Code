import random

n = random.randint(1, 100)  # Randomly selects a number between 1 and 100
guesses = 1  # Initialize the guess counter
a = None  # Initialize `a` to None to enter the loop

while a != n:
    a = int(input("Guess the number: "))  # Prompt the user to guess the number
    if a > n:
        print("Lower number please")
    elif a < n:
        print("Higher number please")
    guesses += 1  # Increment the guess counter after each attempt

print(f"You have guessed the number {n} correctly in {guesses} attempts!")
