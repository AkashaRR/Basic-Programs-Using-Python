questions = ("Which type of Programming does Python support? ",
           "Is Python case sensitive when dealing with identifiers? ",
           "Which of the following is the correct extension of the Python file? ",
           "Which of the following is used to define a block of code in Python language? ")

options = (("A.Object-Oriented Programming", "B.Structured Programming", "C.Functional Programming", "D.All the mentioned"),
           ("A.No", "B.Yes", "C.Machine Dependent", "D.None of the mentioned"),
           ("A..python", "B..pl", "C..py", "D..p"),
            ("A.Indentation", "B.Key", "C.Brackets", "D.All of the mentioned"))

answers = ("D", "B", "C", "A")
guesses = []

score = 0
question_num = 0

for question in questions:
    print("******************")
    print(question)
    for option in options[question_num]:
        print(option)

    guess = input("Enter (A, B, C, D): ").upper()
    guesses.append(guess)
    if guess == answers[question_num]:
        score += 1
        print("Hurray!, CORRECT!!!")
    else:
        print("Oops!!, INCORRECT!!!")
        print(f"{answers[question_num]} is the correct answer")

    question_num += 1

print("************************************")
print("           RESULTS            ")
print("************************************")

print("answers: ", end="")
for answer in answers:
    print(answer, end=" ")
print()

print("guesses: " ,end="")
for guess in guesses:
    print(guess, end=" ")
print()

score = int(score / len(questions) * 100)
print(f"Your Score is : {score}%")
