# String-Programs


# 1.you are given a string made up of parenthesis only.Your task is to check whether parenthesis are balanced or not.If they are balanced print 1 else print 0.
n=input()
a=0
b=0
for i in n:
    if i in '{({':
        a+=1
    if i in '})]':
        b+=1
if a==b:
   print("1")  
else:
   print("0")
   
   
   
   
# 2.You are given two numbers. Your task is to multiply the two numbers and print the answer.
x,y=list(map(int,input().split()))
z=x*y
print(z)

