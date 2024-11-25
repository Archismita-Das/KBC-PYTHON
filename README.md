# KBC-PYTHON
name = input("What is your name?\n")

print("\nGood to have you",name,",Welcome to Kaun Banega Crorepati !\n")
print("Let's start the game!\n")
print("Here is your first question \n")

questions = ["How many days are there in july? ", "Who is the prime minister of India? ","Who wrote Romeo and Juliet? ", "What is the value of 1199+1?"]

answers = ["31", "narendra modi","william shakespeare","1200"]

a = 100000
b = 200000
c = 300000
d = 400000
amount=0

answers1 = input(questions[0])
if answers1.lower() == answers[0]:
    print("Correct answer. You have won", a, "INR\n")
    amount=amount+a
    print("Your total amount is:",amount)
else:
   print("Wrong answer!")


answer2 = input(questions[1])
if answer2.lower() == answers[1]:
        print("Correct answer. You have won", b, "INR\n")
        amount=amount+b
        print("Your total amount is:",amount)
else:
  print("Wrong answer!")


answer3 = input(questions[2])
if answer3.lower() == answers[2]:
    print("Correct answer. You have won", c, "INR\n")
    amount=amount+c
    print("Your total amount is:",amount)
else:
  print("Wrong answer!")

answer4 = input(questions[3])
if answer4.lower() == answers[3]:
   print("Correct answer. You have won", d, "INR\n")
   amount=amount+d
   print("Your total amount is:",amount)
else:
  print("Wrong answer!")

print("Congrats You won:",amount)

print("It was fun to play with you",name,"\nThank you!")