# Python Manual Lab

# Module-4

# EXP-01 Exception Prevention Using pass

# Aim:

To prevent a program from throwing an error by using the pass statement appropriately.

# Algorithm:

Create a list.
Attempt an operation that may cause an error.
Use pass to avoid interruption in program execution.
Print the list.
End the program.

# Program:

```
a = [1, 3, 5]
try:
    a.get()
except:
    pass

print(a)
```

# Output:

<img width="1182" height="262" alt="image" src="https://github.com/user-attachments/assets/feda0258-463c-4b5e-a573-8e9fe377b21b" />

# EXP-02 Pet Class and Move Method

# Aim:

To create a class named Pet with a method move() that prints the animal's movement.

# Algorithm:

Define a class named Pet.
Create a method named move().
Read the pet name from the user.
Create an object of the class.
Call the move() method.
Display "<pet_name> is moving!".

# Program:

```
class pet:
    def move(self,a):
        self.a=a
    def animal(self):
        print(self.a,"is moving!")
        print(self.a)
a=input()
obj=pet()
obj.move(a)
obj.animal()
```

# Output:

<img width="1188" height="358" alt="image" src="https://github.com/user-attachments/assets/8e017d00-1629-4adb-8313-1c1274b24655" />

# EXP-03 Dictionary Creation Using Divisors

# Aim:

To create a dictionary where keys are numbers entered by the user and values are their divisors.

# Algorithm:

Read ten integers from the user.
Create an empty dictionary.
For each number:
Find all divisors of the number.
Store the number as the key and its divisors as the value.
Repeat until all ten numbers are processed.
Display the dictionary.

# Program:

```
def dictDiv(num):
    dict1={}
    divsNum=[]
    for i in num:
        for j in range(1,i+1):
            if(i%j==0):
                divsNum.append(j)
        dict1[i]=divsNum
        divsNum=[]
    print(f"The dictionary is : d =  {dict1}")
val=[]
for _ in range(10):
    num=int(input())
    val.append(num)
dictDiv(val)
```

# Output:

<img width="1185" height="766" alt="image" src="https://github.com/user-attachments/assets/41a16df6-74ae-4aa0-a4f6-f6e02e29ba2e" />

# EXP-04 Addition and Division Using Class

# Aim:

To perform addition and division operations using a class and menu-driven choices.

# Algorithm:

Define a class named saveetha.
Create method setvalues() to store two numbers.
Create method add() to perform addition.
Create method div() to perform division.
Read values of a and b.
Display menu options.
Read the user's choice.
If choice is 1, perform addition.
If choice is 2, perform division.
If choice is 0, print "Exiting!".
Otherwise, print "Invalid choice".
End the program.

# Program:

```
class SEC():
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def add(self):
        return self.a+self.b
    def div (self):
        return self.a//self.b
a=int(input())
b=int(input())
obj=SEC(a,b)
choice=1
while choice!=0:
    choice=int(input())
    if choice==1:
        print("Result: ",obj.add())
    elif choice==2:
        print("Result: ",obj.div())
    elif choice==0:
        print("Exiting!")
```

# Output:

<img width="1187" height="452" alt="image" src="https://github.com/user-attachments/assets/5f13b951-ff5f-4064-bcee-80660519bcbc" />

# EXP-05 List Operations

# Aim:

To write a Python program to find the sum of all elements in a list.

# Algorithm:

Create the list [14,16,18,22].
Initialize a variable sum to 0.
Traverse each element in the list.
Add each element to sum.
Display the total sum.
End the program.

# Program:

```
a=[14,16,18,22]
sum=0
for i in a:
    sum+=i
print(sum)
```

# Output:

<img width="1183" height="267" alt="image" src="https://github.com/user-attachments/assets/6c2a9388-12f0-4cdc-ba88-97d666c2b863" />


