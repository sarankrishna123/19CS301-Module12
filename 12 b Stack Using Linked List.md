# Ex.No 12.b Stack Using Linked List – Push and Index Display

## Aim

To write a Python program to insert 3 elements into a stack and display the index value of each element stored in the stack.

## Algorithm

1. Start  
2. Create a stack  
3. Append elements to the stack  
4. Use a loop to print the index and value of each element in the stack  
5. Print the result  
6. Stop

## Program

```
reg no:212223070023
name: Saran Krishna P S
stack = []

for i in range(3):
    val = input(f"Enter element {i+1}: ")
    stack.append(val)

print("\nStack elements with index values:")
for index, value in enumerate(stack):
    print(f"Index {index}: {value}")

```

## Output
![image](https://github.com/user-attachments/assets/c13a1e98-291c-411b-ad34-4a4b953cf56a)


## Result
thus the program is executed successfully.
