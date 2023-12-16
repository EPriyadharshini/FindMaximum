# Find the maximum of a list of numbers
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
Developed by:priyadharshini.E 
RegisterNumber: 23012593
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: priyadharshini.E 
RegisterNumber: 23012593
'''
def max_marks(marks):
    large = max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: priyadharshini.E 
RegisterNumber: 23012593
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
<img width="263" alt="image" src="https://github.com/EPriyadharshini/FindMaximum/assets/144870831/62ddcc7a-bd31-411a-a4ee-27a4235f1b4a">
<img width="260" alt="image" src="https://github.com/EPriyadharshini/FindMaximum/assets/144870831/74e91071-5d67-4bba-b490-90f0809e38ee">
<img width="269" alt="image" src="https://github.com/EPriyadharshini/FindMaximum/assets/144870831/d5a4571c-3fc8-478e-9d17-51407c667706">

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
