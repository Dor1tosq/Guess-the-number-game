# Guess-the-number-game
import random

while True:
    random_number = random.randint(1, 5)
    user_number = int(input('Угайдай число (от 1 до 5):'))

    if user_number == random_number:
        print('Вы угадали!')
        break
    else:
        print('Вы не угадали')
        print(f'Было загадано число {random_number}')
