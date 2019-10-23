## Introductio to Data Structures For Interviews Notes - Bianca Gandolfo

> Data Structure is a way to organize or format data in a computer.

## Types of Data Structures
- Arrays & Strings
- Hash Tables
- Linked Lists
- Stacks & Queue
- Tree & Heaps
- Graphs

> One important difference between Strings and Array is that a string is immutable meaning it cannot be changed at any given point whereas an array can be modified in order to change a string a new string needs to be created.

### Stacks
Stores data in a last in first out order(LIFO). E.g A stack of plates

```js
const stack = [1,2,3,4];

stack.push(5);
// [1,2,3,4,5]

stack.pop();
// => 5
// [1,2,3,4]
```

### Queue
Stores data in a First in First out order(FIFO). E.g a queue at the bank.

```js
const queue = [1,2,3,4];

queue.enqueue(5);
// [1,2,3,4,5]

queue.dequeue();
// => 1
// [2,3,4,5]
```

### Linked List
A linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list.

Keywords: *pointer* *head* and *tail*

```js
const linkedList = {
  head: {
    value: 1
    next: {
      value: 2
      next: {
        value: 3
        next: null
      }
    }
  }
}
```

### Hash Tables


### Arrays and Strings



## Implementation