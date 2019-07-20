# XOR---Doubly-linked-list
# Memory Efficient
# Traversing,Reversing and Sorting (using bubble sort)
- An ordinary Doubly Linked List requires space for two address fields to store the addresses of previous and next nodes.
- A memory efficient version of Doubly Linked List can be created using only one space for address field with every node. 
- This memory efficient Doubly Linked List is called XOR Linked List or **Memory Efficient** as the list uses bitwise XOR operation to save   space for one address.
- In the XOR linked list, instead of storing actual memory addresses, every node stores the XOR of addresses of previous and next nodes.

- **Sorting this xor linked list**
1. step1 : convert this xor - doubly linked list into singly linked list by changing xor part 
2. step2 : sort this singly linked list using bubble sort
3. step3 : convert this sorted singly linked list into xor - doubly linked list by traversing

   - **Conditions for sorting**
   - without changing data field of any node and changing only head pointers of nodes

- **XOR Properties used while traversing**
> Commutative: A ⊕ B = B ⊕ A
  - This is clear from the definition of XOR: it doesn’t matter which way round you order the two inputs.

> Associative: A ⊕ ( B ⊕ C ) = ( A ⊕ B ) ⊕ C
  - This means that XOR operations can be chained together and the order doesn’t matter. If you aren’t convinced of the truth of this      statement, try drawing the truth tables.

> Identity element: A ⊕ 0 = A
  - This means that any value XOR’d with zero is left unchanged.

> Self-inverse: A ⊕ A = 0
  - This means that any value XOR’d with itself gives zero.
   
- **B ⊕ ( A ⊕ B ) = A**


