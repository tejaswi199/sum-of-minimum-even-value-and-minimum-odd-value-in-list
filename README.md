#Approach-1
n=int(input())
a=list(map(int,input().split()))
e=[]
o=[]
for i in range(n):
  if a[i]%2!=0:
    e.append(a[i])
  elif a[i]>0:
    o.append(a[i])
print(min(e)+min(o))

#Approach-2
n=int(input())
a=list(map(int,input().split()))
e=[]
o=[]
for i in a:
  if i%2!=0:
    e.append(i)
  elif i>0:
    o.append(i)
print(min(e)+min(o))

#Approach-3
n=int(input())
a=list(map(int,input().split()))
e=[0]
o=[0]
for i in a:
  if i%2!=0:
    e.append(i)
  elif i>0:
    o.append(i)
print(min(e)+min(o))
print(max(e)+max(o))
