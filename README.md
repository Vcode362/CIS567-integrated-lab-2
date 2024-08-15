# CIS567-integrated-lab-2
8.7 LAB: Count characters
user_phrase=input()
letter=user_phrase[0]
if letter in user_phrase:
    if user_phrase.count(letter)>2:
        print (f'{user_phrase.count(letter)-1} {letter}\'s')
    elif user_phrase.count(letter)==1:
        print(f'0 {letter}\'s')
    else:
        print(f'{user_phrase.count(letter)-1} {letter}')
        
