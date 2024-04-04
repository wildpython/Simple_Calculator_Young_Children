# Simple_Calculator_Young_Children
This simple calculator is intended for very young children using simplified python code. 
import time

while True: #CREATE A LOOP
    print("\nWELCOME TO YOUR SIMPLE CALCULATOR! \U0001F603 \n")  #SIMPLE WELCOME MESSAGE FOR VERY YOUNG USERS AGED 4 TO 9 YEARS OF AGE
    cont = input("Are you 9 years of age or younger? y/n:\n").lower() #PROMPT THE USER FOR THEIR AGE #ALLOW BOTH UPPER AND LOWER INPUT FOR n and N to end program
    if cont == "n":
        print("Then you will enjoy the more advanced calculator for older children!")
        break #END PROGRAM FOR OLDER USERS

    name=str(input("What is your name?\n")) #PERSONALISE THE CALCULATOR FOR VERY YOUNG USER
    print("Ok "   +name, ",let me show you some basic mathematics!")
    print("\U0001F601")

    time.sleep(4)
    print("Maths is super fun!: \n") #MAKE THE EXPERIENCE SIMPLE AND USE FUN WORDS
    time.sleep(3) #GIVE THE USER EXTRA TIME TO FOLLOW THE TEXT
    print("Lets count some rabbits!") #USE ANIMALS NAMES FOR THE USER TO MAKE THE EXPERIENCE MORE ENGAGING
    print("(+) Example of Addition: 1 rabbit + 1 rabbit = 2 rabbits")
    time.sleep(3)
    print("\U0001f407 \U0001f407 \n")
    time.sleep(3)
    print("Lets subtract some ducks!")
    print("(-) Example of Subtraction: 10 ducks - 5 ducks = 5 ducks")
    time.sleep(3)
    print("\U0001F986 \U0001F986 \U0001F986 \U0001F986 \U0001F986 \n")
    time.sleep(3)
    print("Lets multiply some cute kittens!")
    print("(*) Example of Multiplication: 3 kittens x 3 kittens = 9 kittens")
    time.sleep(3)
    print("\U0001F431 \U0001F431 \U0001F431 \U0001F431 \U0001F431 \U0001F431 \U0001F431 \U0001F431 \U0001F431 \n")
    time.sleep(3)
    print("Lets divide some farm eggs!")
    print("(/) Example of Division: 12 eggs / by 2  = 6 eggs remaining")
    time.sleep(3)
    print("\U0001F95A \U0001F95A \U0001F95A \U0001F95A \U0001F95A \U0001F95A \n")
    time.sleep(3)
    print("Ready?...ok, let's have some fun with numbers! \n")
    time.sleep(3)

    print("Please select the mathematical calculation you want to perform?")  # "User Instruction"
    print("1. for (+) Addition")  # ONLY USE 4 MATHEMATICAL OPTIONS TO KEEP IT SIMPLE
    print("2. for (-) Subtraction")
    print("3. for (*) Multiplication")
    print("4. for (/) Division")

    operation = input()
    if operation == "1":
        num1 = input("Enter first number:")  #USER INSTRUCTION
        num2 = input("Enter second number:")  #USER INSTRUCTION
        print("The sum is: " + str(float(num1) + float(num2)))

    elif operation == "2":
        num1 = input("Enter first number:")
        num2 = input("Enter second number:")
        print("The difference is: " + str(float(num1) - float(num2)))

    elif operation == "3":
        num1 = input("Enter first number:")
        num2 = input("Enter second number:")
        print("The sum is: " + str(float(num1) * float(num2)))

    elif operation == "4":
        num1 = input("Enter first number:")
        num2 = input("Enter second number (not 0):")
        print("The answer is: " + str(float(num1) / float(num2)))

    else:
        print("Invalid Entry")

        cont = input("Would you like to continue? y/n:") #GIVE THE USER AN OPTION TO END THE PROGRAM
        if cont == "n":
            break #THIS BREAKS THE PROGRAM

#THIS CODE HAS BEEN SIMPLIFIED AND MADE CLEANER FOR A SIMPLE CALCULATOR
