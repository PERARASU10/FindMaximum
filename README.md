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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: PERARASU M
RegisterNumber: 212222100033
'''
#marks=input()
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: PERARASU M
RegisterNumber: 212222100033
'''
def max_marks(marks):
   large=max(marks)
   return large



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: PERARASU M
RegisterNumber: 212222100033
'''
def max_marks(marks):
    max=marks[0]
    for i in marks:
        if i>max:
            max=i
    return max



```


## Output:
i)

![1](https://user-images.githubusercontent.com/118348589/236610104-741104ed-0aa6-49ae-a219-213c3771c257.png)

ii)

![2](https://user-images.githubusercontent.com/118348589/236610115-2f2b0753-bfa6-4263-ba8f-7019fb822c6d.png)

iii)

![3](https://user-images.githubusercontent.com/118348589/236610157-fd619799-37c7-43a3-8a5e-db6b83528ebb.png)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
