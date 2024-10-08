# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                          
### REGISTER NUMBER : 212222040139

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### i.)do…while: 

```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
```

### ii.) while…do 

```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")

```

### iii.) switch 

```
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 

```

### iv.) if else

```
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) 

```

### v.) for

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```

### Output:
## 1) DO..WHILE
![373507730-34231620-cd07-41b7-a4e8-d16aaacc2da4](https://github.com/user-attachments/assets/17cfa1d1-35a3-46f6-9bfb-12a50d06d577)

![373507993-e240d6e6-727b-4746-8fde-3599c0f29222](https://github.com/user-attachments/assets/e2769327-1475-438e-9845-ae866163654b)

## 2)WHILE..DO:
![373508161-41d03de3-7b7f-4507-aced-e80d3e8b8512](https://github.com/user-attachments/assets/56d81d7a-564b-4b83-8973-d72abd6cbeed)

![373508191-0cfea109-c051-48ef-9e66-d1dba335563d](https://github.com/user-attachments/assets/0d4e7a71-03aa-4ded-8dd0-9b86b21a64cd)

## 3)SWITCH:
![373508242-70f0baa4-9272-43d1-86a3-02dd02d94895](https://github.com/user-attachments/assets/f70f255e-5b11-4ea5-bc91-15b8aa4d47c2)

## 4) IF-ELSE:
![373508355-73450c00-1bee-4b2a-a672-9b23499bc616](https://github.com/user-attachments/assets/2f50b3ff-07e7-480e-b36c-339b3c24603a)

## 5) FOR:
![373508438-939ad955-780c-44b5-b986-a55eb968dcd6](https://github.com/user-attachments/assets/798536c9-6f25-4908-8812-ea2725b1458c)

## Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
