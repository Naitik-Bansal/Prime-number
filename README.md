p = int(input('the number to check : \n'))
prime = True
for i in range (p):
    if (p==2 or p==3 or p==5):
        prime = True
    elif (p==1 or p%2 ==0 or p%3 ==0 or p%5==0) :
        prime = False
    
if prime :    
    print("yes , it is a prime number")
else :
    print ("no , it is not prime")
