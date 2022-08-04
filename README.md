**Calculators**
Calculators using python

*******Identify the type of Temperature******

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
    

*********Convert of Temp from Farenheit to Celcious and vice versa******

x =float(input('please enter the temp :'))
y = str(input('please specify the unit (C = Celsius and F = Fahrenheit):'))


if y =='c'or y=='C':
    print("the temp in Fahrenheit is:",9/5*(x+32))
elif y =='F' or y=='f':
    print('the temp in Celsius is :', 5 / 9 * (x - 32))
else:
    print('invalid unit')
 
 
 *********Write a program that asks the user to enter a length in centimeters. If the user enters a negative
length, the program should tell the user that the entry is invalid. Otherwise, the program
should convert the length to inches and print out the result. There are 2.54 centimeters in an
inch******

x = int(input('please enter len in cm :'))

if x==-abs(x): # so in if statement or in any statements if we are compare to negative numbers then -abs should be used
    print('invalid entry')
else:
    print('cm to inches:', x*2.54)


*********A year is a leap year if it is divisible by 4, except that years divisible by 100 are not leap years
#unless they are also divisible by 400. Write a program that asks the user for a year and prints
#out whether it is a leap year or not.****

Leap year Calculater

x = int(input('please enter a year :'))

if x%100==0 and x%400==0:
    print('this is a leap year as it is divided by 400')

elif x%4==0 and x%100==0:
    print(' this is not a leap year as it also divided by 100')

elif x%4==0:
    print('this is a leap year')

else:
    print('this is not an leap year')
    
 #########Maxim and Min####################
    
largest = int(input("enter a +ve number :"))
for i in range(5):
    x = int (input('enter a number:'))
    if x>largest:
        largest = x
print('largest number :', largest)
    
    
    
