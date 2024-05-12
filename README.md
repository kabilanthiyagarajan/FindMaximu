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

'''
name:kabilan T 
ref no: 212222230059
'''
def max_marks(array):
    return max (array)

```

ii)	# To find the maximum marks using the list method max().
```Python
'''
name:kabilan T
ref no: 212222230059
'''
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
           max1=array[i]
    return max1


```

iii) # To find the maximum marks without using builtin functions.
```Python
'''
name:kabilan T 
ref no: 212222230059
'''

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1


```

## Output:

i) # To find the maximum of marks using the list method sort.
![Screenshot 2024-05-13 020024](https://github.com/kabilanthiyagarajan/FindMaximu/assets/120206067/bc9a1113-85bc-463c-a0ca-9cf3b8429c3e)


ii) # To find the maximum marks using the list method max().
![Screenshot 2024-05-13 020038](https://github.com/kabilanthiyagarajan/FindMaximu/assets/120206067/faa0d9d9-d40c-4334-84ed-277f28bc9def)


iii) # To find the maximum marks without using builtin functions.
![Screenshot 2024-05-13 020051](https://github.com/kabilanthiyagarajan/FindMaximu/assets/120206067/cdc4fbc6-30e9-4c08-ba78-05c068c6332f)


## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
