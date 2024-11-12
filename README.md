# 123456
a=int(input("what a is it?"))
b=int(input("what b is it?"))
c=int(input("what c is it?"))
m=b**2-4*a*c
if m >0:
    x1=(-b+(m**0.5))/2*a
    x2=(-b+(m**0.5))/2*a
    print("there are two roots, one is x1= ,the other is x2=")
elif m == 0:
    x=(-b)/2*a
    print("only one root,x=")
else:
    print("there are no roots")
