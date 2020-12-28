# Hangman
print('This is a game of hangman')
print('Guess the correct word')
print('Word Hint: It sometimes has a stuffed crust and sometimes it is deep dish')
word = 'pizza'
correctLetters = []

while True:
    user = input('Enter here:')
    if user in 'pizza':
        print('correct')
        correctLetters.append(user)
    if user not in 'pizza':
        print('incorrect')
    if len(correctLetters) == 5:
        print('Congrats you have won')
