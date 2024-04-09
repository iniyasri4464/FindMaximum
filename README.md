
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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    max_marks=max(marks)
    return max_marks


```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    max= marks[0]
    for i in marks[1:]:
        if i > max:
            max = i
    return max



```



## Output:
i)
![alt text](<WhatsApp Image 2024-04-09 at 5.55.35 PM.jpeg>)

ii)
![alt text](<WhatsApp Image 2024-04-09 at 5.57.29 PM.jpeg>)

iii)
![alt text](<WhatsApp Image 2024-04-09 at 5.57.15 PM.jpeg>)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
