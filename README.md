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

#Write a program to mark the maximum of marks using the list method sort.
#Name:Harshini Y
#Register num:212223240050
def max_marks(array):
    array.sort()
    return array[-1]

```

ii)	# To find the maximum marks using the list method max().
```Python

#Write a program to find the maximum marks using the list method max().
#name:Harshini Y
#register num: 212223240050
def max_marks(array):
    return max (array)

```

iii) # To find the maximum marks without using builtin functions.
```Python

#Write a program to find the maximum marks without using builtin functions.
#name:Harshini Y
#register num: 212223240050
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
           max1=array[i]
    return max1

```



## Output:
![image](https://github.com/harshiniyu/FindMaximum/assets/144979786/175b34f9-2c3c-4316-ad23-1d2fefb3d705)

![image](https://github.com/harshiniyu/FindMaximum/assets/144979786/5076cf75-c9e9-4789-a1d7-eec59dbfa757)

![image](https://github.com/harshiniyu/FindMaximum/assets/144979786/31de394a-c5e5-40ee-ad7b-2d556e6a338f)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
