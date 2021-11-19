# Factor.repo
#A program to check for even or odd factors.
num = 60
for i in range(1,num+1):
    rem = num%i

    if(rem == 0):
        if(num%2 == 0):
            print("The Factor is Even:",i)
        else:
            print("The Factor is Odd:",i)

print("For every Factor is either Even or Odd\nwhat do you think?")

ans = input("Input Yes or NO here: ",)
print(ans)

print("A factor is a number that divides the given number without any remainder")
