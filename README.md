# find-range
n=int(input("Enter the Limit"))
if n%2==0:
    for i in range(n-1,0,-2):
        print(i)
else:
    for i in range(n,0,-2):
        print(i)

OUTPUT:

Enter the Limit20
19
17
15
13
11
9
7
5
3
1
