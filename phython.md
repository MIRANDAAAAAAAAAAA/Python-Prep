phython


# QUESTION 1 

The following shows a sample of data from the file:
10, 200, 5

20, 100, 1

30, 150, 12

15, 250,8


01 inventory = open("inventory.txt", 'r')

02 eof = False

03 while eof == False:

04     line = inventory.readline()

05

06

07             print(line)

08     else:

09         print("End of file")

10         eof = True05  if line != '':

11         inventory.close()


ANSWER
    05  if line != '':

    06      if line != '\n':

````````````````````````````````````````````````````````````````````````````````````````````

# QUESTION 2

Which line can be used instead of the comment to cause the snippet to produce the following expected output? (Select all that apply)
Code:

z, y, x = 2, 1, 0

x, z = z, y

y = y - z

# put line here

print(x, y, z)

Expected output:
0, 1, 2

ANSWER
     x, y, z = y, z, x

    z, y, x = x, z, y

``````````````````````````````````````````````````````````````````````````````````````````
QUESTION 3

employee_number = "sentinel"


while employee_number != "":
      

valid = False


valid = True

```````````````````````````````````````````````````````````````````````````````````````````
QUESTION 4

No change is needed


````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 5

Which two data types are stored in the rooms dictionary at line 01?
    int: str

What is the data type of room at line 02?
    str

Why does line 03 fail to find the rooms?
    Mismatched data types

 `````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 6
 print(“Congratulations on ” + str(int(end)-int(start)) + “ years of service!” )

```````````````````````````````````````````````````````````````````````````````````````
QUESTION 7

float(input("Enter next rating (1-5) or -1 for done "))
print("The average star rating for the NetVerZleep coffee is: "
format(average, '.2f'))

````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 8

age == None:  rating = "C"
age < 13:  rating = "C"
age < 18:  rating = "T"
 rating = "A"

 ````````````````````````````````````````````````````````````````````````````````````````````

 QUESTION 9

After executing code segment 1, the data type of variable a is str.

    Yes

 

After executing code segment 2, the data type of varialbe b is float.

    Yes

 

Ager executing code segment 3, the data type of variable c is int.

    No

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 10

What is displayed after the first print?

    False

 

What is displayed after the second print?

    False

 

What is displayed after the third print?

    True

 

What is displayed after the fourth print?

    True

````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 11

math.floor(x)
math.fabs(x)

````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 12

import random
randints=[random.randint(1,7) for i in range(1,8)]

```````````````````````````````````````````````````````````````````````````````````````````

QUESTION 13

['3', '3', '3', '3', '3']

``````````````````````````````````````````````````````````````````````````````````````````

QUESTION 14

It will print a random int value from 0 to 5

````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 15

totalItems = int(input(“How many items would you like?”))

`````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 16

Parentisis
Exponents
Unary posotive,neggitive,not
Multiplication and Division
Addition and Subtraction
And

`````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 17

Place the notes after the # sign on any line

`````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 18

type(+1E10)
float

type(5.0)
float

type("True")
str

type(False)
bool

``````````````````````````````````````````````````````````````````````````````````````````

QUESTION 19

while
break

````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 20

age = 2
int

minor = False
bool

name = "Contoso"
str

weight = 123.5
float

zip = "81000"
str

`````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 21

!= "n":
== "Sunday":
== "Thursday":

```````````````````````````````````````````````````````````````````````````````````````````` QUESTION 22


p = 2
while p <= 100:
    is_prime = True

for i in range(2, p):
    if p i == 0:
        is_prime = False

break

if is_prime == True:
    print(p)

p = p + 1

````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 23

if a >= 0:
else:
if a % 2 == 0:
else:

````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 24

int
float

````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 25

Line 06

Line 07

Line 08

`````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 26

while (index < 10) :
if numbers[index] == 6 :

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 27

open(“local_data”, “w”)

`````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 28

b * c
addition
(a + (b * c)) - d

```````````````````````````````````````````````````````````````````````````````````````````` QUESTION 29

if grade >= 90:
elif grade >= 80:
elif grade >= 70:
elif grade >= 65:
else:

`````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 30

01 def get_name():
04 def calc_calories(miles, calories_per_mile):

`````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 31
name = input()

``````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 32

random.randint(5, 11)
random.randrange(5, 12, 1)

``````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 33

employees [0:-5]
employees [:-5]

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 34

15

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 35

print(a % b)

    3
Prompt 2print(a // b)

    2
Prompt 3print(a / b)

    2.75

`````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 36

name = input("Enter your name: ")

else: print(name, "is lower case.")

else: print(name, "is upper case.")

else: print(name, 'is mixed case.')

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 37
b = (-a)**2

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 38

word in word_list

letter in word

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 39


from math import sqrt as squareRoot

````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 40

if os.path.isfile(filename):

with open(filename, 'r') as file:

return file.readline()

else:

return None
`````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 41

def update_score
(current, value):
return current

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 42

3

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 43

bool

``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 44


print(n, end="  ")
``````````````````````````````````````````````````````````````````````````````````````````````

QUESTION 45

125

```````````````````````````````````````````````````````````````````````````````````````````
QUESTION 46

'Peter\'s sister\'s name\'s \"Anna\"'

"Peter's sister's name's \"Anna\""

``````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 47

512
``````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 48 

%-20s
%4.1f

`````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 49

Yes
No
No

``````````````````````````````````````````````````````````````````````````````````````````````
QUESTION 50

TRUE

TRUE

TRUE

FALSE
``````````````````````````````````````````````````````````````````````````````````````````````
 

 