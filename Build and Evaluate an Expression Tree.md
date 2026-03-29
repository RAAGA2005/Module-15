# Ex. No: 15E - Build and Evaluate an Expression Tree

## AIM:
To write a Python program to build and evaluate the given Expression tree.

---

## ALGORITHM:

1. **Start the program.**
2. Create nodes for operators and operands.
3. Build the expression tree by connecting nodes in the correct hierarchical structure.
4. Define a recursive function `evaluate(root)`:
   - If the node is a number (leaf), return it.
   - Else, recursively evaluate left and right subtrees.
   - Apply the operator at the current node to the results.
5. Return the final result from the root node.
6. **End the program.**

---

## PROGRAM:

```
from binarytree import build,Node
x=['/','*','+','+',4,'-',2,3,1,None,None,9,5]
t=build(x)
print(t.inorder)
print(t.postorder)
```

## OUTPUT:
<img width="1151" height="249" alt="image" src="https://github.com/user-attachments/assets/bd7b7268-3422-4a7f-adb3-85891ba88674" />


## RESULT:
output verified for the Python program to build and evaluate the given Expression tree.
