# calculate1
import math

def calc(a,b,c):
    return result

while 1:
    a,b,c=map(int,input('please input three integers:').split()) 
    dt=b**2-4*a*c
    if (dt >= 0):
        x1=(-b+math.sqrt(dt))/(2*a)
        x2=(-b-math.sqrt(dt))/(2*a)
        result=x1,x2
    else:
        result='无实数根！'
    print(calc(a,b,c))

