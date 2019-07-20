# XOR---Doubly-linked-list
# Memory Efficient
# Traversing,Reversing and Sorting (using bubble sort)
An ordinary Doubly Linked List requires space for two address fields to store the addresses of previous and next nodes.
A memory efficient version of Doubly Linked List can be created using only one space for address field with every node. 
This memory efficient Doubly Linked List is called XOR Linked List or *Memory Efficient* as the list uses bitwise XOR operation to save space for one address.
In the XOR linked list, instead of storing actual memory addresses, every node stores the XOR of addresses of previous and next nodes.

*For sorting this xor linked list* 
step1 : convert this xor - doubly linked list into singly linked list by changing xor part 
step2 : sort this singly linked list using bubble sort
step3 : convert this sorted singly linked list into xor - doubly linked list by traversing
*Conditions for sorting*
without changing data field of any node and changing only head pointers of nodes
