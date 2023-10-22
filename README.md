# linked-lists

Creating a linked list data structure and its functions.


## Summary
This project contains two factory functions called `Node`, which returns the node value and next pointer, and `LinkedList`, which contains head and all of its functions:
```javascript
function Node(v = null, next = null) {
  return {
    value: v,
    next: next,
  }
}

function LinkedList() {
  return {
    head: null,

    // Append new node at the end of the list with value(v)
    append(v) {
      // ...code
    },

    // Prepend new node at the beginning of the list with value(v)
    prepend(v) {
      // ...code
    },

    // Return total number of nodes in the list
    size() {
      // ...code
    },

    // Return the first node in the list
    findHead() {
      // ...code
    },

    // Return the last node in the list
    tail() {
      // ...code
    },

    // Return the node at the given index
    at(index) {
      // ...code
    },

    // Remove the last element from the list
    pop() {
      // ...code
    },

    // Return true if the value is in the list and otherwise returns false
    contains(v) {
      // ...code
    },

    // Return the index of the node containing value, or null if not found
    find(v) {
      // ...code
    },

    // Print the linked list to the console
    toString() {
      // ...code
    },

    // Insert new node with the provided value at the given index
    insertAt(v, index) {
      // ...code
    },

    // Remove the node at the given index
    removeAt(index) {
      // ...code
    },
  }
}
```

I manually tested each function by creating a `list` variable and running each function with different values. 
```javascript
const list = LinkedList();
list.append(2);
list.prepend(1);
list.prepend(0);
list.append(3);
list.append(4);
list.append(5);
list.size();
list.findHead();
list.tail();
list.at(1);
list.pop();
list.size();
list.contains(4);
list.find(4);
list.toString();
list.insertAt('insert', 3);
list.toString();
list.removeAt(4);
list.toString();
```

