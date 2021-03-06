## dsa-projekt1

This is a project for 2nd semester class "Data Structures and Algorithms". Projects is about working with dynamic memory allocation.

**memory_init() (initialization of memory):**
 - [x] redirect global pointer to array representing memory
 - [x] allocate head and foot of memory
 - [x] allocate pointers to previous and next free blocks of memory
 
 **memory_alloc() (allocation of block of memory):**
 - [x] best fit: find a free block of memory with size closest to size of allocated block
 - [x] allocate head and foot of memory block
 - [x] return pointer to allocated block of memory
 - [x] error handling
 
 **memory_free() (deallocation of already allocated block of memory):**
 - [x] validate pointer
 - [x] free block of memory
 - [x] add neighboring blocks of free memory together
 - [x] alter pointers pointing to previous and next blocks of free memory
 - [x] error handling
 
 **memory_check() (validation of pointer pointing to allocated block of memory):**
 - [x] check validity of pointer pointing to allocated block of memory
 - [x] testing
 
 ## testing
 - [x] blocks of same size (8 - 24) in memory with size 50, 100 or 200 bytes
 - [x] blocks of different size (8 - 24) in memory with size 50, 100 or 200 bytes
 - [x] blocks of different size (500 - 5 000) in memory with size at least 1 000 bytes
 - [x] blocks of different size (8 - 50 000) in memory with size at least 1 000 bytes
