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
![Screenshot 2024-05-08 065706](https://github.com/KrishnaPrasad148/Sorting-Algorithms/assets/147332763/8c4f519a-22c7-4296-ae21-ef07301f4f8f)


### ii)
![Screenshot 2024-05-08 065723](https://github.com/KrishnaPrasad148/Sorting-Algorithms/assets/147332763/e966b229-a54d-4111-bc68-3402cd698b76)





## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
