
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
![image](https://github.com/iniyasri4464/FindMaximum/assets/152419072/48a4843f-3c3e-41ba-8333-50f8dcce0933)
![image](https://github.com/iniyasri4464/FindMaximum/assets/152419072/1c879da6-7654-47d8-98c6-ba72c5199800)
![image](https://github.com/iniyasri4464/FindMaximum/assets/152419072/edc4982e-efa4-4db2-ba47-698794bc74aa)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
