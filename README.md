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
```Python
## Registration No: 212223230076
## Nmae:            HEMAVATHY S
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
## Registration No: 212223230076
## Nmae:            HEMAVATHY S
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python

## Registration No: 212223230076
## Nmae:            HEMAVATHY S
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark

```



## Output:
![Screenshot 2024-04-06 143916](https://github.com/Hemaatchu/FindMaximum/assets/147328300/63c07db8-5f05-40ca-be8a-e4f0a561e611)
![Screenshot 2024-04-06 143941](https://github.com/Hemaatchu/FindMaximum/assets/147328300/5127729f-695d-478b-89ec-79bc30660c90)
![Screenshot 2024-04-06 143958](https://github.com/Hemaatchu/FindMaximum/assets/147328300/2a3aceb9-3e62-419e-9fb8-37a4a37b8805)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
