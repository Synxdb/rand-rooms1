import random

def roomGen():
    num = random.randrange(0.80)
    if num < 20:
        print(1)
    elif num < 40:
        print(2)
    elif num < 60:
        print(3)
    else:
        print (4)      

def roomescription():
    if roomGen == (1):
        print ("Kitchen")
    if roomGen == (2):
        print ("Living room")
    if roomGen == (3):
        print ("Engine room")
    if roomGen == (4):
        print ("Storage")
        
