# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
```
Developed By : S.Krishna Prasad
Register No: 212223230108
```
i)	#Selection Sort
```
lst = eval(input())
for i in range(len(lst)):
    for j in range(i+1,len(lst)):
        if lst[j]<lst[i]:
            temp = lst[i]
            lst[i] = lst[j]
            lst[j] = temp
print(f"Sorted list using Selection sort {lst}")

```
ii)	#Insertion Sort
```
lst = eval(input())
for i in range(len(lst)):
    for j in range(len(lst)-1):
        if lst[j]>lst[j+1]:
            temp = lst[j]
            lst[j] = lst[j+1]
            lst[j+1] = temp
print(f"Sorted list using Insertion sort {lst}")

```

## Output:
### i)
#### Input:
[12, 34, 7, 45, 86, 8]
#### Output:
![image](https://github.com/KrishnaPrasad148/Sorting-Algorithms/assets/147332763/7827ae51-8145-4d98-ba53-23c5d1032632)

### ii)
#### Input:
[9, 12, 5, 8, 16, 4]

#### Output:
![image](https://github.com/KrishnaPrasad148/Sorting-Algorithms/assets/147332763/c669f119-20c0-486c-8d3c-a97add77d3d1)




## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
