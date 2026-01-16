# basic_python
#it uses  for commenting in programe so that people dont forget the mean of command
print("i am a good boy \nand viewer also good boy")# \ it used for seperating lines # ctr+forward for commenting and uncommenting
#''' ssd''' used for multiline commenting
print("i am a \"good boy\"\nand viewer also good in nature")
print ("mahadav", 1 ,2, 3 ,sep="-")# it tells about uses of seperator
print("maha" , 1, 2, 3,sep="+",end=".003")
print("maha" , 1, 2, 3,sep="+",end=".003\n")
print("harry")
#data type in python day 6
#variable is a type of container that hold data , creating a variable like assign a place to variable
# data type specify the type of value variable holds
a=123
print(a)
a1=9
b="harry"
print(b)
print(a+a1)
print("type of a", type(a))
print("type of b",type(b))
# numeric data:int, float,complex
#int.4,5,8,
#float:.321,.025,
#complex.complex no.include it
#text data called string
# boolean data which contain value true and false
#sequenced data :list ,tuple
#list is collection of different data type ,dict. is mapped data
#day 7 complete
#dynamic typing
# in python we dont define the data type in the python
a=5
#static typing here we define the data type in he programmin
#dynamic binding variable can hold different data type

a=5
print(a)
a="nitish"
print(a)
a=1
b=5
c=8
print(a,b,c)
#different method
a,b,c=1,8,5
print(a,b,c)

a=b=c=5
print(a,b,c)



key word and identifier

# key words compilation mean converting a english language in binary language
#identifier=creating a name is called identifier
#identifier writing method
# can't start with digit
name1='ujjwal'
print(name1)# this through an error
# can't use special character except _ under score
# it can't be key words



##temp heading

# static vs dynamic
input('name')
input('gmail')

from enum import StrEnum
#take input from from user and store into variable

#add the two variable
#print the result
fnum=input('enter first number')
snum=input('enter second number')
#print(type(fnum),type(snum))
result=int(fnum) + int(snum)
print(result)
print(type(fnum))

#type conversion

#implict  vs explicit type conversion
print(5+5.6)
print(type(5),type(5.6))
#print(4+'4')



# explicit type connversion
# strin convert ito integer
int('4')
type(int('4'))
int(4.5)
#int(4+5j)
#int to str
str(6)
float(4)



# literal the value which stored into the variable
a=0b1010
#print(a)
b=100  # decimal literal
c=0o310  #octal literal
#print(c)

d=0x12c  #hexadecimal literal
#print(d)



# float literal

10.5
1.5e3

#lecture 2


# arithmatic operator
print(5+6)
print(5-6)
print(5*6)
print(5/2)
print(5//2)# integer division
print(5%2)# gives reminder remainder(modulus operator)
print(5**2)#power operator

# relational operator
print(4>5)# greator than
print(4<5) # less than operator
print(4>=4)
print(4<=4)
print(4==4)
print(4!=4)

# logical operator
print(1 and 0) #if both are true then only true
print(1 or 0) #if any one is true then true
print(not 1)#

# bit wise operator
print(2&3)# and operation
print(2|3) # or operation
print(2^3)# xor operation
print(~3)# not operation
print(4>>2)# right shift
print(2<<3)# left shift



# assignment operator
# =
# a= 2
a=2
#a=a+2
a+=2
print(a)

# a++ ++a not used in python


# membership operator to check the existence of the data
# in/not in
print('d' in 'delhi')
print(1 in [2,3,4,5])

# program   find the sum of three digit number entered by the user in both end we use the co.on

number = int(input('enter three digit number'))
a= number%10  # modulous ( reminder system )

number=number//10 # integer division
b=number % 10
number=number//10
c=number % 10565

print(a+b+c)

# if else program


email=input('enter email')
password=input('enter password')
if email=="ujjwal@gmail.com" and password=="1234":
   print('welcome')
else:
  print('not correct')





# if more than two possibility then we use eliff possibility in starting we and end start with if and end with the else
email=input('enter email')
password=input('enter password')

if email=='ujjwal@gmail.com' and password=='1234':
  print('welcome')
elif email=='ujjwal@gmail.com' and password != '1234':
    #tell the user about the incorrect password
    print('incorrect password')
    passward=input('enter your password again')
    if password =='1234':
      print('finally correct!')


    else:
      print(' beta tumse na ho payega')
else:
  print('not correct')


# min of three number
a=int(input("Enter first num: "))
b=int(input("Enter se23cond num: "))
c=int(input("Enter third num: "))
if a<b and a<c:
 print ('smallest is',a)
elif b<c:
 print('smallest is',b)
else:
  print('smallest is',c)

# module in python
.maths
.keywords
.constant
.random


# maths
import math
math.factorial(5)
#
math.sqrt(196)

# keywords
import keyword
print(keyword.kwlist)

# random
import random
print(random.randint(1,100))


# date time
import datetime
print(datetime.datetime.now())

# loops


# while loop example-> program to print the table it used in hotel listing moblile listing etc
# program sum off all digit of given number
# keep accepting number from all user till he or she enter a 0 the find the average

number=int(input('enter the number'))
j = 1
while j<11:
 print(number,'*',j,'=',number * j)
 j +=1

# problem 3
sellingprice =int(input('enter selling price' ))
costprice=int(input('enter cost price'))
if sellingprice>costprice:
  print('profi',sellingprice-costprice)
else:
  print('loss',costprice-sellingprice)



### `Problem 2`: Write a program that take a user input of three angles and will find out whether it can form a triangle or not.

a1=int(input('enter first angle'))
a2=int(input('enter second angle'))
a3=int(input('enter third angle'))
if a1+a2+a3==180:
  print('valid angle of triangle')
else:
  print('invalid angle')

# problem13
number=int(input(enter number))
if number/1 & number/number &!

###`Problem 12`:Write a program to print whether a given number is a prime number or not

###`Problem 12`:Write a program to print whether a given number is a prime number or not

###`Problem 12`:Write a program to print whether a given number is a prime number or not



# while loop with else
x = 1
while x<5:
 print(x) # here we put here in cooma ther x work as a string
 x +=1
else:
  print('limit crossed')


# gussing code
# generate a random integer between 1 and 100
import random
jackpot=random.randint(1,100)
guess=int(input('enter number'))
if


# for loop it use the mudule range for the gap betbeen the numbeer we give ,and write the number


for i in range(1,11):
  print(i)


name=['a','b','c']
score=[50,40,50]
plt.bar(name,score)
plt.title('score by name')
plt.show()


num=int(input('enter number'))
if num % 2 ==0:
 print('even')
else:
  print('odd')


num=int(input('enter number'))
if num>0:
 print('positive')
elif num==0:
  print('zero')
else:
  print('negative')


year=int(input('enter year'))
if year%4==0:
  print(' leap year')
else:
  print("not leap year")



a=int(input('enter first number'))
b=int(input('enter second number:'))
if a>b:
  print('a is greater')
else:
  print('b is greater')

currpop_city=10000
for i in range(10,0,-1):
  print(i,currpop_city)
  currpop_city=currpop_city/1.1


# sequence sum
# code here
n=int(input('enter number'))

result=0
fact=1
for i in  range(1,n+1):
 fact=i*fact
 result=result+i/fact
 print(result)


# nested loop

#nested loop meaning loop within loop
# if some one saying thagt print name of student name from 1 to 12 class wise
# then we we run a loop for class then one for student
for i in range (1,3):
  for j in range (1,3):
    print(i,j)


# CODE
row =int(input('enter number of rows'))
for i in range(1,row+1):
  print('*')

row= int(input('enter number of rows'))
for i in range(1,row+1):
  for j in range(1,i+1):
    print('*',end='')
  print()

row =int(input('enter number of rows'))
for i in range(1,row+1):
  for j in range(1,i+1):
    print(j,end='')
  print()



row =int(input('enter number of rows'))
for i in range(1,row+1):
  for j in range(1,i+1):
    print(j,end='')
  for k in range(i-1,0,-1):
      print(k,end='')
  print()




  print()

# loop control statement
.break
.continue
.pass


# break
lower= int(input('enter lower range'))
upper= int(input('enter upper range'))

for i in range(lower,upper+1):
  for j in range(2,i):
    if i%j==0:
      break
  else:
    print(i)

# CONTINUE
for i in range (1,10):
  if i==5:
    continue
  print(i)

# pass

# string


# indexing
# positive indexing start from left to right and start from 0 while  negative indexing start from the right with the -1 sign
m= 'ujjwal'
print(m[0])

# slicing when we need more than one character
s='hello world'
print(s[1:5])

m='ujjwal'
print(m[-2])

# continue
for i in range(1, 10):
  if i==5:
    continue # in continue we see that break in the series at the specification while at in break  after that whole series will break

  print(i)





print("m")#
a=500
b=6
print("a","+","b","is",a+b)
print("a","-","b","is",a-b)
print("a","*","b","is",a*b)
print("a","/","b","is",a/b)
# day 8 calculator
# day 9
a="9"
a=9
b="12"
b=12
print(a+b)
print(int(a)+int(b))
# int use to convert to into integer
# the conversion of one data type into the another data typeis known as casting in python
#python support a wide variety of function or method like int, float str ord hex oct tuple
# it two type of typecasting
# explicit conversion 2 implicit conversion
# explicit conversion  is done by coader
# implict typecasting   one data type convert in another data type. it done by python it self
a=2.36
b=2
print (a+b)# here a is float data type so here python convert it self


