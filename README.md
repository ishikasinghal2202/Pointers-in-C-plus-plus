# Pointers-in-C-plus-plus
AIM:

     To study pointers in C++


OBJECTIVE:

     They provide a powerful way to directly access and manipulate memory, making them essential for:

                     -Dynamic memory allocation
                     -Efficient data handling
                     -Low-level programming


THEORY:

      POINTERS-
               A pointer is a special variable that stores the memory address of another variable.
               If x is a variable, then a pointer to x stores the address where x is located in memory.

      Accessing and Dereferencing-
             -Address-of operator (&): Retrieves the memory address of a variable.
             -Dereference operator (*): Accesses the value at the address stored in the pointer. 

     Pointer Arithmetic-
             - Pointers can be incremented or decremented to move between memory locations, based on the size of the data type they point to.

     Null Pointers-
             - A null pointer points to nothing and is often used for safety.

     Pointers and Arrays-
             - Arrays and pointers are closely related. The array name itself acts as a pointer to the first element.
                  int arr[3] = {10, 20, 30};
                  int* p = arr;
                  cout << *(p + 2);  // prints 30


     Pointers to Pointers-
             - A pointer that stores the address of another pointer.
                   int x = 5;
                   int* p = &x;
                   int** pp = &p;


     Dynamic Memory Allocation
              - Using new and delete to allocate and deallocate memory during runtime.
                   int* p = new int;  // allocates memory
                   *p = 100;
                   delete p;          // frees memory


SAMPLE OUTPUT:

     Traversal of an array-
               Original array:
               10 20 30 40 50 
               Traversed array:
               50 40 30 20 10 

    Character printing of strings:
              Enter a string:
              Hello 
              Characters of string entered are:
              H
              e
              l
              l
              o

    Basic pointer arithematic:
             Data type: int.
             Value of a: 2
             Initial address of a: 0x7ffe08ddab8c
             Incremented address of a: 0x7ffe08ddab90

             Data type: bool.
             Value of b: 1
             Initial address of b: 1
             Incremented address of b: 2

             Data type: double
             Value of c: 10.5
             Initial address of c: 0x7ffe08ddab80
             Incremented address of c: 0x7ffe08ddab88

             Data type: float.
             Value of d: 23
             Initial address of d: 0x7ffe08ddab7c
             Incremented address of d: 0x7ffe08ddab80

    Addition & Subraction using pointer:
            The difference between the values at index 4 and 2 is:20
            The addition of the values of array at index 4 and 2 is:80

CONCLUSION:

         Pointers in C++ are fundamental for low-level memory access, efficient data handling, and dynamic memory management.
         While powerful, pointers require careful handling to avoid errors such as dangling pointers and memory leaks.
         A solid grasp of pointers is crucial for advanced programming areas like data structures, system programming, and performance optimization.

              
