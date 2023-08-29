# Speed-Limit-Test
# cook your dish here
for i in range (int(input())):
    a,x,b,y = map(int,input().split())
    c = a/x
    d = b/y
    if(c>d):
        print("Alice")
    elif(c==d):
        print("Equal")
    else:
        print("Bob")
