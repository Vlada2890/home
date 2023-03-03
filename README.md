# home
with open('name.txt', 'w') as file:
    file.write('Hello, world!')

with open('name.txt', 'r') as file:
    a = file.read()
    print(a)

with open('name.txt', 'w') as file:
    file.write('Hello again!')

dic = {'wow': 15, 'live': 22, 'love': 34}
with open('dic.txt', 'w') as file:
    for key, value in dic.items():
        file.write(f'{key}: {value}\n')

import os
os.remove('dic.txt')
