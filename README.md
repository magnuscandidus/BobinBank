# BobinBank
t=int(input())
while t:
    w,x,y,z=map(int,input().split())
    print(w+((x-y)*z))
    t-=1
