#Mohamed Mahfoudhi
from numpy import array
nbgre=int(input(""))
t=array([0]*nbgre)
nbtours=int(input(""))

for i in range(nbtours) :
    num_g=int(input(""))
    dis=int(input(""))
    for j in range(nbgre) :
        if num_g-1==j :
            t[j]=t[j]+dis
ma=t[0]
print(t)
indx=0
for i in range(1,nbgre) :
    if t[i]>ma :
        ma=t[i]
        indx=i
        
    if t[i]>ma and t[i]==ma :
        if i<i-1 :
            indx=i
        else :
            indx=i-1
    
if indx!=0 :    
    print(indx+1)
else :
    print(indx+1)
    
    
            
    
    
    
    
