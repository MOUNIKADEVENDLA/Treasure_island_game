print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
choice1 = input('\nLets get started!\n\nChoose "Left" or "Right"\n').lower()
if choice1 == "left":
  choice2 = input('\nYou need to reach the castle.Which one do you want to select?\n\n "Swim" or "Boat"\n').lower()
  if choice2 == "boat":
    choice3 = input('You have reached the castle.\nThere are three doors.Select any one of the them:\n\n"Red" or "Yellow" or "Blue"\n').lower()
    if choice3 == "red":
      print("Oh my god fire!!!.\nGAME OVER.")
    elif choice3 == "yellow":
      print("Yay!Congratulations you found the treasure.")
    elif choice3 == "blue":
      print("Uh-oh, angry beasts\nGood luck next time.\nGAME OVER.")
    else:
      print("'Type the correct key.'")
  elif choice2 == "swim":
    print("Oops,You got drowned.\nGAME OVER.")
  else:
    print("'Type the correct key.'")
elif choice1 == "right":
  print("Sorry,you fell into a hole.\nGAME OVER.")
else:
  print("'Type the correct key.'")
