# RoboSpeaker
Using this project you can speak by typing what you want to speak


import os
if __name__ == '__main__':
    print("Welcome to RoboSpeaker 1.0")
    while True:
        x = input("Enter what you want to speak :")
        command = f"say {x}"
        os.system(command)
        if x == "q":
            break
