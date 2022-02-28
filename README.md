# feb-28-ass-2
Assignment-2
x=[1,2,1,3,2,4,2,5,4,6,5,7,6,4]
l=[]
for i in x:
    if i not in l:
        if x.count(i)==1:
            l.append(i)
print(l)

Output:
[3,7]
