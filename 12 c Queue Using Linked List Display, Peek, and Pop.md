# 12 c Queue Using Linked List – Display, Peek, and Pop

## Aim

To write a Python program to insert 3 elements into a queue and display each element with its index.

## Algorithm

1. Start  
2. Create a queue  
3. Append elements to the queue  
4. Use a loop to print each element and its index  
5. Stop

## Program

```
reg no:212223070023
name:saran krishna P S
import queue

q = queue.Queue()

q.put('Element 1')
q.put('Element 2')
q.put('Element 3')

index = 0
while not q.empty():
    element = q.get()
    print(f"Index: {index}, Element: {element}")
    index += 1


```

## OUTPUT
![Screenshot 2025-05-21 104314](https://github.com/user-attachments/assets/703160b2-b1b3-49ef-b080-5543a08fe02d)

## RESULT
thus the program is executed successfully.
