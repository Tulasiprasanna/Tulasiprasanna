d=input()
l=list(d)
print(l)
res=[]
for i in l:
    if i not in res:
    res.append(i)
for i in res:
    print(i,end=" )"
