n=int(input('enter n'))
for i in range(1,n+1):
    for j in range(1,i+1):
         print(j,end=" ")
    print("\n")
for i in range(1,n+1): 
    for j in range(n,i,-1): 
       print(n-j+1,end=" ")
    print("\n")
