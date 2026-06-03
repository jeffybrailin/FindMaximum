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
<img width="448" height="145" alt="image" src="https://github.com/user-attachments/assets/2d93845d-c89a-4631-8d1e-3989b79507bd" />

ii)	# To find the maximum marks using the list method max().
```
a=list(map(int,input().split()))
print(max(a))


```
<img width="456" height="135" alt="image" src="https://github.com/user-attachments/assets/1a38e772-a982-4039-a988-759816ca0b7f" />

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
<img width="518" height="143" alt="image" src="https://github.com/user-attachments/assets/4c44e7ab-39b4-485b-a787-2e6d17df4680" />

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
