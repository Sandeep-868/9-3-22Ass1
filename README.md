# 9-3-22Ass1
x=input()
u=0
l=0
d=0
s=0
for i in x:
    if(i.islower()):
        l+=1
    elif(i.isupper()):
        u+=1
    elif(i.isdigit()):
        d+=1
    else:
        s+=1
print("lower letter:",l)
print("upper letter:",u)
print("digit:",d)
print("symbol:",s)
