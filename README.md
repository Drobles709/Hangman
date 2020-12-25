# Hangman
A game of hangman
print('This is a game of hangman')
print('Guess the correct word')
word = pizza

while True:
  user=input('Enter here:')
  if user in 'pizza':
    print('correct')
    correctLetters.append(user)
  else:
  print('incorrect')
