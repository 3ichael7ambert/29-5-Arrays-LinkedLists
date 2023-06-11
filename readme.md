# Arrays and Linked Lists

    Run this in terminal
```bash
npm install jest
npm run
```



This code defines a `Node` class and a `LinkedList` class in JavaScript. Here's a breakdown of the code:

### Node: node for a singly linked list.
The `Node` class represents a single node in a linked list. Each node has a `val` property to store the value and a `next` property to reference the next node in the list.

### LinkedList: chained together nodes.
The `LinkedList` class represents a singly linked list. It has properties `head` and `tail` to keep track of the first and last nodes in the list, and a `length` property to store the number of nodes in the list.

The `LinkedList` class has several methods to manipulate the list:

- `push(val)`: Adds a new node with the given value to the end of the list.
- `unshift(val)`: Adds a new node with the given value to the start of the list.
- `pop()`: Removes and returns the value of the last node in the list.
- `shift()`: Removes and returns the value of the first node in the list.
- `getAt(idx)`: Returns the value of the node at the specified index.
- `setAt(idx, val)`: Sets the value of the node at the specified index to the given value.
- `insertAt(idx, val)`: Inserts a new node with the given value at the specified index.
- `removeAt(idx)`: Removes and returns the value of the node at the specified index.
- `average()`: Calculates and returns the average of all values in the list.

At the end of the code, the `LinkedList` class is exported using `module.exports`, indicating that it can be imported into other files using the `require` function.

You can use this `LinkedList` class to create and manipulate linked lists in your JavaScript applications.
