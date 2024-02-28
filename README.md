# even-add
# approach1
n=int(input())
a=list(map(int,input().split()))
r=0
for i in range(n):
  if a[i]%2==0 and a[i]>r:
    r=a[i]
print(r)

# approach2
n=int(input())
c=list(map(int,input().split()))
r=0
for i in c:
  if i%2==0 and i>r:
    r=i
print(r)
# approach3
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in range(n):
  if a[i]%2==0:
    r.append(a[i])
print(max(r))
# approach4
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in a:
  if i%2==0:
    r.append(i)
print(max(r))
# approach5
n=int(input())
a=list(map(int,input().split()))
r=0
for i in range(n):
  if a[i]%2!=0 and a[i]>r:
    r=a[i]
print(r)

# approach6
n=int(input())
a=list(map(int,input().split()))
r=0
for i in range(n):
  if i%2!=0 and i>r:
    r=i
print(r)

# approach7
#sum of max even no & max odd no
n=int(input())
a=list(map(int,input().split()))
e=0
o=0
for i in range(n):
  if a[i]%2==0 and a[i]>e:
    e=a[i]
  elif a[i]>o:
    o=a[i]
print(e+o)

# approach8
n=int(input())
a=list(map(int,input().split()))
e=0
o=0
for i in a:
  if i%2==0 and i>e:
    e=i
  elif i>o:
    o=i
print(e+o)

# approach9
n=int(input())
a=list(map(int,input().split()))
e=[]
o=[]
for i in range(n):
  if a[i]%2==0:
    e.append(a[i])
  else:
    o.append(a[i])
print(max(e)+max(o))


# approach10
n=int(input())
a=list(map(int,input().split()))
e=[]
o=[]
for i in a:
  if i%2==0:
    e.append(i)
  else:
    o.append(i)
print(max(e)+max(o))    

# average of max&min even&odd numbers
# approach11
n=int(input())
a=list(map(int,input().split()))
es=0
c=0
for i in range(n):
  if a[i]%2==0 and a[i]>es:
    es=es+a[i]
    c=c+1
print(es//c)

# approach12
# average of even numbers
n=int(input())
a=list(map(int,input().split()))
e=[]
for i in range(n):
  if a[i]%2==0:
    e.append(a[i])
print(sum(e)//len(e))

# approach13
n=int(input())
a=list(map(int,input().split()))
e=[]
for i in a:
  if i%2==0:
    e.append(i)
print(sum(e)//len(e))




