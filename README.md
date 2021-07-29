# Virtual-Memory-Manager

This project aims at providing an opportunity to design and implement a standalone virtual memory manager, where there is a software-managed TLB.
This program:
- loads a file containing a list of logical addresses,
- translates logical addresses into physical addresses for a virtual address space of size 2^16 = 65,536 bytes, and
- outputs the value of the byte stored at the translated physical address
