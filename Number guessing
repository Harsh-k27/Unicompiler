text = "WELCOME!!"
text2 = "Guess the right number to win, You have limited chances"
print(text.center(80))
print(text2.center(80))

def guess_number(i,s,a):                
    g = 50
    N = int(input("Guess the number:-"))
    if(i<11):
        if(N == g):
            print("WOW!! You got it correct")
            print(f"you took {i} attempts, {a} left\n")
            print(f"Your score is = {s}\n")

        elif(N in range(0,40)):
            print("OOPS! Not Quiet, try again")
            a = a-1
            print(f"The number is larger than this and is multiple of ten, attempts used {i}, {a} left\n")
            s = s-10
            print(f"Your score is = {s}\n")
            i = i+1
            guess_number(i,s,a)

        elif(N in range(g-10,g-1)):
            print("OOPS! Not Quiet, try again")
            a = a-1
            print(f"You are close, The number is slightly larger than this, attempts used {i}, {a} left\n")
            s = s-10
            print(f"Your score is = {s}\n")
            i = i+1
            guess_number(i,s,a)

        elif(N in range(g+1, g+10)):
            print("OOPS! Not Quiet, try again")
            a = a-1
            print(f"You are close, The number is slightly smaller than this, attempts used {i}, {a} left\n")
            s = s-10
            print(f"Your score is = {s}\n")
            i = i+1
            guess_number(i,s,a)

        elif(N in range(60,100)):
            print("OOPS! Not Quiet, try again")
            a = a-1
            print(f"The number is smaller than this, attempts used {i}, {a} left\n")
            s = s-10
            print(f"Your score is = {s}\n")
            i = i+1
            guess_number(i,s,a)
    else:
        print("GAME OVER!!!")

        print(f"Your score is {s}\n")  

i = 1
s=100
a=10
guess_number(i,s,a)
