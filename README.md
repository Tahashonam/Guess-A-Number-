# Guess-A-Number-
its a game !
copy this code to your vs code or python or ...


    import os
    import random

    os.system("cls")
    number = random.randint(1, 100)
    attemps = 0

    while True :
        guess = int(input("Guess a number between 1 and 100 : "))
        attemps += 1


        if guess < number :
            print("Guess a higher number : ")
        elif guess > number :
            print("Guess a lower number : ")
        else :
            print(F"Congratulations! You finally guessed the number {number} in {attemps} attempts")
