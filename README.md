# patterns-6
a = []
r,c=map(int,input().split(" "))
for i in range(r):
  x = []
  for j in range(c):
    x.append("*")
  a.append(x)
for i in a:
  print(*i,sep=" ")
