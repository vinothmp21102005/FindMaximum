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


#program to find the maximum mark using list method sort
#Developed by : VINOTH M P
#Register number : 212223240182

def max_marks(marks):
    marks.sort()
    return marks[-1]




```

ii)	# To find the maximum marks using the list method max().
```Python

#program to find the maximum mark using list method max
#Developed by : VINOTH M P
#Register number : 212223240182

def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python

#program to find the maximum mark without using built in function
#Developed by : VINOTH M P
#Register number : 212223240182

def max_marks(marks):
    max_mark = marks[0]
    for i in marks:
        if i > max_mark:
            max_mark = i
    return max_mark


```



## Output:
program 1:
![alt text](<Screenshot 2024-04-09 053840.png>)

program 2:
![alt text](<Screenshot 2024-04-09 054357.png>)

program 3:

![alt text](<Screenshot 2024-04-09 054809.png>)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
