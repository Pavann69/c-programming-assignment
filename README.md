# c-programming-assignment
@ -0,0 +1,124 @@
// Question 1- What do you mean by arrays? Give one example of arrays. How you can declare an array in code?
// Answer 1- An array os collection of elements of the same data type stored at continuous memory locations.
// Example - 
#include <stdio.h>
int main() { 
int marks [5]={80,75,90,85,70};
// Declaring an array -
   int numbers [5]; // Declares an integer array of 5 elements



//  Question 2 - What do you mean by functions. Type of functions. Give one example of code in each type.
// Answer 2 - A function in C is a block of code that performs a specific task.
// Types of function -
// 1. Library Function - these are built-in function provided by C .
#include <stdio.h>
#include <math.h>

int main() {
    double num = 16.0;
    double result = sqrt (num); // sqrt() is a library function 
    
    printf("Square root of %.2f is %.2f",num, result);

    return 0;
}
//Output -
Square root of 16.00 is 4.00

//2. User-defined Function - these are functions created by the programmer.
#include <stdio.h>
void add (int a ,int b) {
        printf("Sum = %d\n",a+b);
}
int main () {
        add (5,10);
        return 0;
}
// Output -
Sum = 15


// Question 3 - What do you mean by pointers?How can you initialize a pointer?
// Answer 3 - A pointer is a variable that stores the memory address of another variable.
// Initializing a pointer -
#include <stdio.h>
int main ( ) {
        int arr[]={1,2,3,4,5};
        int *ptr = arr;
        printf("%d\n",*ptr);
        
        return 0;
}
//Output -
1

//Question 4 - What are the types of array write in a code?
//Answer 4 - 1. 1-D Array - stores elements in a single row.
#include <stdio.h>
int main( ) {
         int arr[5]={10,20,30,40,50};   // 1D array of integers 
         for (int i = 0;i<5;i++){
                 printf("arr[%d]=%d\n",i,arr[i]);
         return 0;
}
//Output -
arr[0]=10
arr[1]=20
arr[2]=30
arr[3]=40
arr[4]=50

//2.2-D Array - stores elements in rows and columns.
#include <stdio.h>
int main ( ) {
        int matrix[2][3]={
                  {1,2,3},
                  {4,5,6}
        };
        for (int i = 0;i<2;i++){
                  for(int j = 0;j<3;j++){
                            printf("%d", matrix [i][j]);
                  }  
                  printf("\n");
         } 
         return 0;
}
// Output -
123
456

//Question 5 - Explain the types of operators in code .
// Answer 5 - Types of operators in C -
#include <stdio.h>
int main() {
    int a = 10, b = 5;

    // Arithmetic
    printf("Sum: %d\n", a + b);

    // Relational
    printf("Is a greater than b? %d\n", a > b);

    // Logical
    printf("Both positive? %d\n", (a > 0 && b > 0));

    // Assignment
    a += 2;
    printf("After assignment: %d\n", a);

    // Increment
    b++;
    printf("After increment: %d\n", b);

    // Ternary
    int max = (a > b) ? a : b;
    printf("Greater value: %d\n", max);

    return 0;
}
//Output -
Sum: 15
Is a greater than b? 1
Both positive? 1
After assignment: 12
After increment: 6
Greater value: 12
