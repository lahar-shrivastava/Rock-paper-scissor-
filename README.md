# Rock-paper-scissor-
A simple command-line Rock-Paper-Scissors game built using Python's random module and conditional logic.
Python
"rock 1 paper 2 scissor 3"

import random

computer= random.choice(["r","p","s"])
dic={"r":"Rock","p":"Paper","s":"Scissor"}
c=input("Enter r=Rock, p=Paper or s=Scissor: ").lower()
youc= {"Rock":"r","Paper":"p","Scissor":"s"}
you =c
print("you chose: ",dic[you])
print("you chose: ",dic[computer])
if(computer==you):
    print("It's Draw........")
elif(computer=="r" and you=="p"):
    print("YAyyyyyyyyy!!!! You Won")
elif(computer=="p" and you=="r"):
    print("You Lost,Better Luck Next Time")
elif(computer=="p" and you=="s"):
    print("YAyyyyyyyyy!!!! You Won")
elif(computer=="s" and you=="p"):
    print("You Lost,Better Luck Next Time")
elif(computer=="s"and you=="r"):
    print("YAyyyyyyyyy!!!! You Won")
elif(computer=="r" and you=="s"):
    print("You Lost,Better Luck Next Time")
