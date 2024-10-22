## **Linked Lists**

A **linked List** is used to represent sequential data. Linear order is not given by their physical placement in memory. Instead each element contains an address of the next element. Each node contains: data, a reference(link) to the next node in the sequence.Arrays have better cache locality as compared to linked lists.

A drawback of linked lists is that access
time is linear (and difficult to pipeline). Faster
access, such as random access, is not feasible.

### **Singly Linked List**

### **Doubly Linked List**

Pros
* e
* y

Cons
* l
* y

Access time is linear (and difficult to pipeline). Faster
access, such as random access, is not feasible. Arrays
have better cache locality as compared to linked lists.

A **Pointer** is a reference to another place memory
A **Node** is a bucket of data

### Pseudo-code for Basic Operations

### Traverse

```text
Traverse(head)
  Pre: head is the head node in the list
  Post: the items in the list have been traversed
  n ← head
  while n != ø
    yield n.value
    n ← n.next
  end while
end Traverse
```

## prepend

## append

## lookup

## insertAt

## removeAt

## clear

# Corner cases

- Empty linked list (head is null)
- Single node
- Two nodes
- Linked list has cycles.
  Tip: Clarify beforehand with the interviewer whether there can be a cycle in the list. Usually the answer is no and you don't have to handle it in the code

# Implementations
[JS]()
```
```

[Python]()

```
```


## Complexities

### Time Complexity

| Access | Lookup | Insert(at) | Deletion |
|:------:|:------:|:----------:|:--------:|
|  O(n)  |  O(n)  |    O(1)    |   O(n)   |

### Space Complexity

O(n)

## Related Questions
| No | Problem Statement                                                         |
|----|---------------------------------------------------------------------------|
| 1. | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) |
|    |                                                                           |

## References

# Articles

1.  [Medium](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)

# Videos

2.  [Coursera](https://www.coursera.org/lecture/data-structures/singly-linked-lists-kHhgK)
