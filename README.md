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
Program developed by:V RAKSHA DHARANIKA,



Register number:212223230167.


i)	# To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
     large=max(marks)
     return large

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    maximum=marks[0]
    for i in marks:
        if(i>maximum):
            maximum=i
    return maximum

```



## Output:
## using the list method sort:

![Screenshot (103)](https://github.com/rakshadharanika/FindMaximum/assets/149348380/06629173-e7be-4c5a-9f2b-63e1493ea6bf)

## using the list method max():
![Screenshot (104)](https://github.com/rakshadharanika/FindMaximum/assets/149348380/48c7dcba-cb74-4648-8e5c-8928d8134635)
## using builtin functions:
![Screenshot (105)](https://github.com/rakshadharanika/FindMaximum/assets/149348380/ba07d7bc-f160-468c-8c30-3e3fde7e872e)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
