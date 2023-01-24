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
Program to mark the maximum of marks using the list method sort
Developed by:  Shriram S
RegisterNumber:  22008494
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: Shriram S
RegisterNumber: 22008494
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: Shriram S
RegisterNumber: 22008494
'''
def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number > max):
            max = number
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://user-images.githubusercontent.com/117991122/214348368-747988eb-d65f-4539-8edf-ebb6ea8b6784.png)

Program to find the maximum marks using the list method max().
![image](https://user-images.githubusercontent.com/117991122/214348646-f4c8652c-5fa1-4778-847f-cd0c19011f72.png)

Program to the maximum marks without using builtin functions.
![image](https://user-images.githubusercontent.com/117991122/214348881-ec85cf5a-d124-4caf-9beb-28c5a7106513.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
