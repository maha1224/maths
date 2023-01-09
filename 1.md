a = int(input('enter the coefficent of x^3:'))
b = int(input('enter the coefficent of x^2:'))
c = int(input('enter the coefficent of x:'))
d = int(input('enter the coefficent of constant:'))

for i in range(-10,10):
    res = a*(i)**3 + b*(i)**2 + c*(i) + d
    if(res == 0):
        print('one of the root is:',i)
