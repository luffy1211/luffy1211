import random
user_wins= 0
computer_wins= 0

while True:
    user_input= input("type Rock/paper/scisor or Q to quit").lower()
    if user_input == 'q':
        quit()
     if user_input in ['rock', 'paper', 'scisor']:
