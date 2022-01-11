# witchTest
#How do you know she is a witch?

print('We found a witch, may we burn her?')
looks = ' '
while looks != 'She looks like one!':
    print('How do you know she is a witch?')
    looks = input()
print('Did you dress her up like this? Y/N')
dressUp = input()
if dressUp == 'N':
    print("She's a witch! Burn her!")
else:
    print('What makes you think she is a witch?')
newt = input()
while newt != 'Well, she turned me into a newt!':
    continue
print('A newt?')
better = input()
while better != 'I got better':
    continue
print('Burn her anyway!')
print('There are ways of telling whether she is a witch.')
print('What do you do with witches?')
witches = input()
while witches != 'Burn them!':
    witches = input()
    continue
print('And what do you burn apart from witches?')
answer1 = input()
if answer1 == 'wood':
    print('So, why do witches burn?')
elif answer1 == 'More witches!':
    print('close!')
    answer1 = input()
else:
    print('Have you seen this movie?')
    answer1 = input()
burn = input()
if burn == 'Because they are made of wood':
    print('Good!')
else:
    burn = input()
print('So, how do we know she is made of wood?')
answer2 = input()
if answer2 == 'Build a brige out of her':
    print('Ah, but can you not build bridges out of stone?')
    answer2 = input()
else:
    print('Does wood sink in water? Y/N')
answer3 = input()
if answer3 == 'Y':
    print('Are you sure?')
    answer3 = input()
if answer3 == 'N':
    print('No...Throw her into the pond!')
print('What also floats in water?')
duck = input()
while duck != 'a duck':
    print('Try Again')
if duck == 'a duck':
    print('Exactly')
print('So if she weighs the same as a duck, shes made of wood')
print('And therefore...')
therefore = input()
if therefore != 'A Witch!':
    print('Try again')
    therefore = input()
else:
    print('Congrats! you reached the end!')
