# Linked List Learning Guide

## 1. Introduction to Linked List
A **linked list** is a linear data structure where elements (called nodes) are connected using pointers.  
Each node contains:
- **Data** – value stored in the node
- **Next** – reference to the next node in the list

### Types of Linked Lists:
1. **Singly Linked List** – each node points to the next.
2. **Doubly Linked List** – nodes have pointers to both previous and next nodes.
3. **Circular Linked List** – last node points back to the head.

**Why Linked List?**
- Dynamic size (no need to predefine capacity like arrays).
- Efficient insertions and deletions (O(1) if reference to node is known).

---

## 2. Common Operations on Linked List

| Operation | Singly LL | Doubly LL | Time Complexity | Space Complexity |
|-----------|-----------|-----------|-----------------|------------------|
| Insert at Head | O(1) | O(1) | O(1) | O(1) |
| Insert at Tail | O(n) | O(1) | O(n) / O(1) | O(1) |
| Delete Node | O(n) | O(n) | O(n) | O(1) |
| Search Element | O(n) | O(n) | O(n) | O(1) |
| Reverse List | O(n) | O(n) | O(n) | O(1) |
| Traverse | O(n) | O(n) | O(n) | O(1) |

---

## 3. LeetCode Practice Problems (Linked List)

Here are **15 important LeetCode problems** to practice:

1. [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)
2. [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/)
3. [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)
4. [Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/)
5. [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)
6. [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)
7. [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)
8. [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)
9. [Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/)
10. [Rotate List](https://leetcode.com/problems/rotate-list/)
11. [Partition List](https://leetcode.com/problems/partition-list/)
12. [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
13. [Reorder List](https://leetcode.com/problems/reorder-list/)
14. [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)
15. [Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/)

---

# Advanced / Design-Oriented Linked List LeetCode Problems

---

## 1. [LRU Cache](https://leetcode.com/problems/lru-cache/)
**Description:** Design a cache with `get` and `put` operations in O(1), using **HashMap + Doubly Linked List**.

---

## 2. [LFU Cache](https://leetcode.com/problems/lfu-cache/)
**Description:** Similar to LRU, but remove **least frequently used** instead of least recently used. Uses **HashMap + Linked List + Frequency Count**.

---

## 3. [Design Browser History](https://leetcode.com/problems/design-browser-history/)
**Description:** Implement browser forward/backward navigation using a **Doubly Linked List**.

---

## 4. [Design Twitter](https://leetcode.com/problems/design-twitter/)
**Description:** Use linked lists for tweet streams (each user has a linked list of tweets).

---

## 5. [All O`one Data Structure](https://leetcode.com/problems/all-oone-data-structure/)
**Description:** Maintain counts in a linked list of buckets to support `inc`, `dec`, `getMaxKey`, and `getMinKey` in O(1).

---

## 6. [Design Linked List](https://leetcode.com/problems/design-linked-list/)
**Description:** Implement your own linked list with operations like add, delete, and get.

---

## 7. [Design Skiplist](https://leetcode.com/problems/design-skiplist/)
**Description:** A probabilistic data structure using multiple levels of linked lists for fast search/insert/delete.

---

## 8. [Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/)
**Description:** Each node may have a child pointer to another linked list → flatten into one list.

---

## 9. [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)
**Description:** Deep copy a linked list where nodes have `next` and `random` pointers.

---

## 10. [Linked List Random Node](https://leetcode.com/problems/linked-list-random-node/)
**Description:** Return a random node’s value with equal probability (**Reservoir Sampling on Linked List**).

---