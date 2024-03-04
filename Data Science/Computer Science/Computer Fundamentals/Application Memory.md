#compsci 
The key parts of application memory are the:

- Stack 
    - Used for function call management and local variables.
    - Memory allocated and deallocated in a Last-In-First-Out (LIFO) order.
    - Fast access to memory.
    - Limited in size compared to the heap.
    - Memory automatically managed by the compiler.
    - Variables created inside a function are stored here.
- Heap

    - Dynamic memory area.
    - Used for allocating memory at runtime.
    - Memory allocation and deallocation are controlled by the programmer.
    - Dynamic data structures like arrays, linked lists are often stored here.
    - Manual memory management using functions like `malloc` and `free` in languages like C.
    - Automatic memory management in languages like Java or Python.
- Global/Static Variables
    - Reserved for global variables and static variables.
    - Exists throughout the program's execution.
    - Global variables are accessible across the entire program.
    - Static variables have a lifetime throughout the program's execution but limited scope.
    - Memory is allocated and initialized only once during the program's lifetime.
- Code / Instructions
	- Area where the executable code resides.
	- Read-only and can't be modified during runtime.
	- Code is typically loaded into memory when the program starts.

