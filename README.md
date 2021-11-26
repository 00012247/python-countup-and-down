# python-countup-and-down
Homework CSF
#  countdown project
def countdown(n):
    if n<=0:
        print("Blastoff!")
    else:
        print(n)
        countdown(n-1)

countdown(20)

# count up
def countup(b):
    if b >=0:
        print("finish")
    else:
        print(b)
        countup(b+1)
countup(-20);
