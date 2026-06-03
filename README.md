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
a=list(map(int,input().split()))
a.sort()
print(a[-1])


```
## Output:
<img width="448" height="145" alt="image" src="https://github.com/user-attachments/assets/d3b795b8-e81d-4732-990b-91576d5635d5" />

ii)	# To find the maximum marks using the list method max().
```
a=list(map(int,input().split()))
print(max(a))


```
<img width="456" height="135" alt="image" src="https://github.com/user-attachments/assets/7608caa6-b5ed-4db1-a21f-25298fb277e6" />

iii) # To find the maximum marks without using builtin functions.
```
a=list(map(int,input().split()))
max=a[0]
for i in a:
    if(i>max):
        max=i
print(max)


```



## Output:
<img width="518" height="143" alt="image" src="https://github.com/user-attachments/assets/e9f83142-b89e-4381-8189-8b2642448e07" />

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
