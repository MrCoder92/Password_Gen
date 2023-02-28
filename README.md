# Password_Gen
Generating random passwords

#Import a in built pyhton library called random

  import random

#Create an initial message for the user
  print('Welcome To Your Password Generator ')

#Create a variable (string) with random characters for your password generation
  values = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!@&%*().,$£_+?0123456789'

#Create a variable to state the number of password to generate at a time
#convert variable to integer to prevent error
  number = input('Amount of password to generate: ')
  number = int(number)

#Create a variable to ask users to input their preferred password length
#Convert it to an integer
  length = input('Provide your password lenght: ')
  length = int(length)

#Execute the command to provide the users' password
  print('\nHere are your passwords: ')

#Use a for loop to get the password the user needs and print it
  for pwd in range(number):
      password = ''
      for c in range(lenght):
          passwords += random.choice(values)
  Print(passwords)
