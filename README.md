## DATE :
## EX NO 6: Find the maximum of a list of numbers
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


# DVELOPED BY: HAREESH R
# REGISTER NUMBER: 212223230068


def max_marks(marks):
  
    marks.sort()
  
    return marks[-1]




```

ii)	# To find the maximum marks using the list method max().
```

# DVELOPED BY: HAREESH R
# REGISTER NUMBER: 212223230068

def max_marks(marks):
    return max(marks)




```

iii) # To find the maximum marks without using builtin functions.
```
# DVELOPED BY: HAREESH R
# REGISTER NUMBER: 212223230068
def max_marks(marks):
   
    max_mark = marks[0]
    
   
    for mark in marks:
        
        if mark > max_mark:
            max_mark = mark
            
    return max_mark






```



## Output:
### i)
![Screenshot 2024-10-15 175401](https://github.com/user-attachments/assets/5fc49d02-61ee-49e1-9cb7-15d58b2c9242)


### ii)

![Screenshot 2024-10-15 175417](https://github.com/user-attachments/assets/f95582f7-af47-40db-a178-0ab1624b7c8a)

### iii)
![Screenshot 2024-10-15 175428](https://github.com/user-attachments/assets/1d4eef08-3390-4f90-b4bc-284d2981cbdc)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
