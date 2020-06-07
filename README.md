from vpython import*
a=0
b=1
while a<10:
    a=b
    b=a+b
    sphere(pos=vector(a,b,0),radius=a) #掛け算の方が割り算よりパソコンにとって軽い
