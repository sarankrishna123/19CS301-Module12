# 12 d Queue Using Linked List – Enqueue and All Operations

## Aim

To write a Python program to add 4 elements to a queue and print the elements present at the front and rear of the queue.

## Algorithm

1. Start  
2. Create a queue  
3. Append elements to the queue  
4. Print the front and rear elements in the queue  
5. Stop

## Program

```
reg no:212223070023
name:Saran Krishna P S
from collections import deque

queue = deque()

for i in range(4):
    val = input(f"Enter element {i+1}: ")
    queue.append(val)

print("\nQueue contents:")
print(list(queue))

if queue:
    print(f"Front element: {queue[0]}")
    print(f"Rear element: {queue[-1]}")
else:
    print("Queue is empty.")



## OUTPUT
![image](https://github.com/user-attachments/assets/22aec6f7-4216-4f36-b2c2-deb273885ab5)

## RESULT
thus the program is executed successfully.
