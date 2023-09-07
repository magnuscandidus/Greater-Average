# Greater-Average
# cook your dish here
for i in range (int(input())):
    x,y,z = map(int,input().split())
    a = (x+y)/2
    if(a>z):
        print("Yes")
    else:
        print("No")
