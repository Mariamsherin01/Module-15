# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```
from binarytree import build
nodes=['*',4,'-',5,'+',2,7]
root=build(nodes)
print(root.inorder)
print(root.postorder)
```

## OUTPUT
![image](https://github.com/user-attachments/assets/316ba4c1-5e69-4c3d-a030-6a72a2613731)


## RESULT
Thus, The Python program to build the given expression tree and print the inorder and postorder traversals was implemented and executed successfully.
