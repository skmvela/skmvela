import random

num = random.randint(1,100)
print("is your age "+ str(num))
x = str(input("is it" + "less", "more", "correct"))

if x == str(less):
    print(1,num-1)
elif x == str(more):
    print("no")
elif x == str(correct):
   if num < 18:
     print("damn you young")
   else:
     print("damn you old")
