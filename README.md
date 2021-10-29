# Binary-Tree


A binary search tree requires that the values stored by the left child are less than the value of the parent, and the values stored by the right child are greater than that of the parent.


Implementing a  BinaryTree class containing value, left and right child nodes and a depth.

An **insert()** method to add and place a value at the correct location in the binary tree.


```If the new value is less than the root node's value
  If a left child node doesn't exist 
    Create a new BinaryTree with the new value at a greater depth and assign it to the left pointer
  Else
    Recursively call .insert() on the left child node  
Else
  If a right child node doesn't exist
    Create a new BinaryTree with the new value at a greater depth and assign it to a right pointer
  Else
    Recursively call .insert() on the right child node
    
    

A getNodeByValue() method to retrieve a child node by its value or null.



If target value is the same as the current node value
  Return the current node
Else
  If target value is less than the root node's value and there is a left child node
    Recursively search from the left child node
  Else if there is a right child node
    Recursively search from the right child node
    
    
    
A depthFirstTraversal() method to traverse the binary tree using the inorder traversal option.

