# ProyectoUtec
L= [34,55,66,77,90,42,12,23,45,67,93,74,25,33,49,64] 
n=int(input())
contador=0
x=[]
M=[]
while contador<n:
    i=int(input())
    x.append(i)
    contador=contador+1

for a in x:
    M.append(L.index(a))
print(M)
