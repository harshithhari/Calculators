# Calculators
Calculators using python

Identify the type of Temperature

x = float(input("please enter temp in Celcious :"))

if x<-273.15:
    print('invalid entry temp is below absolute zero')
elif x==-273.15:
    print('the temp is absolute')
elif -273.15<x<0:
    print('the temp is below freezing')
elif x==0:
    print('the temp is is at freezing point')
elif 0<x<100:
    print(' the temp is normal')
elif x==100:
    print('the temp is at boiling point')
else:
    print('the temp is above boiling point')
    

Convert of Temp from Farenheit to Celcious and vice versa

x =float(input('please enter the temp :'))
y = str(input('please specify the unit (C = Celsius and F = Fahrenheit):'))


if y =='c'or y=='C':
    print("the temp in Fahrenheit is:",9/5*(x+32))
elif y =='F' or y=='f':
    print('the temp in Celsius is :', 5 / 9 * (x - 32))
else:
    print('invalid unit')
    
    
