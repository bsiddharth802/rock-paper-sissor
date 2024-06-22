import random
user1 = input("enter your option :")
print(user1)
user2 = random.choice(["rock","paper","scissor"])
print(user2)
if user1 == user2:
    print("draw !")
elif user1=="rock" and user2=="paper":
    print("user2 won !")
elif user1=="rock" and user2=="scissor":
    print("user1 won !")
elif user1=="paper" and user2=="rock":
    print("user1 won !")
elif user1=="paper" and user2=="scissor":
    print("user2 won !")
elif user1=="scissor" and user2=="rock":
    print("user2 won !")
elif user1=="scissor" and user2=="paper":
    print("user1 won !")
else:
    print("wrong option , please select rock, paper, scissor any one of the above mentioned option")
