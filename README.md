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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
   large = max(marks)
   return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)
![Screenshot (10)](https://github.com/anushanirudh/FindMaximum/assets/151725737/0b4b3fb6-62dc-45e1-a8aa-15a1de27f88e)

ii)
![Screenshot (11)](https://github.com/anushanirudh/FindMaximum/assets/151725737/02fd87c6-5a73-4eee-8ecb-878812b9571f)

iii)
![Screenshot (12)](https://github.com/anushanirudh/FindMaximum/assets/151725737/67da1179-dc61-4d36-9790-89222a24f7cf)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
