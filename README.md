
n, m = map(int, input().split())
d=[]
e=[]
listout=[]
for i in range (0,n):
    d.append(input())
for j in range (0,m):
    e.append(input())

for i in range(0,m):
    listout=[]
    for j in range(0,n):
        if e[i]==d[j]:
            listout.append(j+1)
    if len(listout)==0:
        print(-1)
    else:
        print(*listout)


    

