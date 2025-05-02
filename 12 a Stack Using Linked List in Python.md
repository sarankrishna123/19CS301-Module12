# 19CS301-Module12
# Ex.No 12.a Stack Using Linked List in Python

This project demonstrates a basic stack implementation in Python using list methods to mimic linked list behavior. It includes stack operations like **push**, **display**, **peek**, and **pop**.

## AIM

To write a Python program to type and display the elements pushed into a stack using a linked list approach.

## ALGORITHM

1. Start  
2. Create a stack  
3. Append (push) elements to the stack  
4. Print (display) the elements of the stack  
5. Stop

## PROGRAM

```
reg no:212223070023
name:Saran Krishna P S
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

class Stack:
    def __init__(self):
        self.top = None
    
    def push(self, data):
        new_node = Node(data)
        new_node.next = self.top
        self.top = new_node
    
    def pop(self):
        if self.is_empty():
            print("Stack is empty!")
            return None
        popped = self.top
        self.top = self.top.next
        return popped.data
    
    def peek(self):
        if self.is_empty():
            print("Stack is empty!")
            return None
        return self.top.data
    
    def is_empty(self):
        return self.top is None
    
    def display(self):
        current = self.top
        if not current:
            print("Stack is empty")
            return
        while current:
            print(current.data, end=" -> ")
            current = current.next
        print("None")

if __name__ == "__main__":
    stack = Stack()
    
    n = int(input("Enter number of elements to push into the stack: "))
    
    for i in range(n):
        val = int(input(f"Enter value {i+1}: "))
        stack.push(val)
    
    print("Stack elements:")
    stack.display()

```
## OUTPUT
![image](https://github.com/user-attachments/assets/ba733070-c7b3-4d71-9638-21314da2a3ef)

## RESULT
thus the program is executed successfully.

