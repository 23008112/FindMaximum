# Find the maximum of a list of numbers
Name: R.Sanjana

Register number: 23008112

Department: AIML
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: R.Sanjana
RegisterNumber: 23008112
'''
#Write your code here
def max_marks(marks):
    marks.sort()
    a=marks[-1]
    return a
    marks=[88,67,77,93,95,11,67,89,56,89]
    #Write your code here



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: R.Sanjana
RegisterNumber: 23008112
'''
# write your code here
def max_marks(marks):
    a=max(marks)
    return a
    marks=[88,67,77,93,95,11,67,89,56,89]
  



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: R.Sanjana
RegisterNumber: 23008112
'''
# write your code here

def max_marks(list1):
    max=0
    for i in list1:
        if(i>max):
            max=i
    return max
list1=[88, 67, 77, 93, 95, 11, 67, 89, 56, 89]
   



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
### (i) using sort
![sort](https://github.com/23008112/FindMaximum/assets/138972470/31800ee4-e23e-43b4-a14c-72dcd6970442)
### (ii) usint max()
![max](https://github.com/23008112/FindMaximum/assets/138972470/849ec173-fb5c-44f2-a43c-31d28dceb407)
### (iii) using builtin function
![function](https://github.com/23008112/FindMaximum/assets/138972470/0130a18d-8340-4d1a-94bd-e5df475ff847)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
