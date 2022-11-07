n=int(input())
l=[]
for i in range(n):
     l.append(int(input()))
l.sort()
print('minimum element='+l[0]+' '+maximum element='+l[-1]+' '+'average='+sum(l)/n)
