# python
patterns in python /#triangle, #diagonal, #heart
#creating triangle
n=int(input("enter any number"))
for i in range(1,n+1):
    for j in range(1,(n+1-i)):
        print(" ",end="")
    for k in range(1,i+1):
        print("*",end=" ")
    print("") 
 #creating diagonal
 n=int(input("enter any number below 20="))
for i in range(1,n+1):
    for j in range(1,(n+1-i)):
        print(" ",end="")
    for k in range(1,i+1):
        print("*",end=" ")
    print("")   
for i in range(1,n+1):
    for j in range(1,i+1):
        print(" ",end="")
    for k in range(1,(n+1-i)):
        print("*",end=" ") 
    print("")    
  #creating heart
  for row in range(6):
    for column in range(7):
        if (row==0 and column%3!=0) or (row==1 and column%3==0) or (row-column==2) or (row+column==8):
            print("*",end="")
        else:
            print(" ",end="")
    print("")        
