### Dynamic-Storage-Allocator-x64

This project contains a custom implementation of a dynamic storage allocator. The system provides functional replacements for the standard C memory management routines, including malloc, free, realloc, and calloc. The implementation was engineered to handle 64-bit address spaces. The objective of this implementation was to manage heap memory by optimizing the trade-off between space utilization and throughput. 

#### Performance Data

* Reached a maximum of 90% of the requested throughput maintaining utilization above the given 55% threshold across all benchmark traces.

#### Development and Tools

* Language: C
* Platform: Linux x86-64
* Debugging: GDB and hprobe helper functions
  
#### Academic Integrity Statement

In compliance with Carnegie Mellon University academic integrity policies, the source code for this project is maintained in a private repository. I am available to discuss the specific data points, performance results, and engineering trade-offs encountered during the development of this allocator.
