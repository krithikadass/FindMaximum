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
#Developed by: M.Krithika Lakshmi
#Register number: 212224230134

def max_marks(array):
    array.sort()
    return array[-1]

```

ii)	# To find the maximum marks using the list method max().
```
#Developed by: M.Krithika Lakshmi
#Register number: 212224230134

def max_marks(array):
    return max(array)

```

iii) # To find the maximum marks without using builtin functions.
```
#Developed by: M.Krithika Lakshmi
#Register number: 212224230134

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1

```



## Output:

![Screenshot 2025-05-07 155404](https://github.com/user-attachments/assets/5afae01d-1e81-4378-82be-ce590b2657c7)

![Screenshot 2025-05-07 155507](https://github.com/user-attachments/assets/22542307-383b-4038-8a39-3fc8d065cbe2)

![Screenshot 2025-05-07 155556](https://github.com/user-attachments/assets/4ee9182f-658d-4b58-b2f3-a95c45661329)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
