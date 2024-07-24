Week 0: Assignment 0
Assignment not submitted
1 point
What is the output of the following C++ code snippet?

#include <iostream>

using namespace std;

 

int main() {

    int x = 10, y = 20;

    int *p = &x;

    *p = y;

    cout << x << " " << y << endl;

    return 0;

}


 a. 20 20
 b. 10 20
 c. 10 10
 d. 20 10
Yes, the answer is correct.
Score: 1
Accepted Answers:
a. 20 20
1 point
If A is a 3 x 3 matrix given by:


					

What is the determinant of A?
 a. 49
 b. 72
 c. 54
 d. -54
Yes, the answer is correct.
Score: 1
Accepted Answers:
b. 72
1 point
Given vectors u=(2,3) and v=(4,-1), what is the dot product u⋅v?
 a. 10
 b. 5
 c. 11
 d. 7
Yes, the answer is correct.
Score: 1
Accepted Answers:
b. 5
1 point
Consider the following C++ code snippet. What will be the output?

	
#include <iostream>

using namespace std;

 

void swap(int &a, int &b) {

    int temp = a;

    a = b;

    b = temp;

}

 

int main() {

    int x = 5, y = 10;

    swap(x, y);

    cout << x << " " << y << endl;

    return 0;

}

 a. 10 5
 b. 5 5
 c. 10 10
 d. 5 10
Yes, the answer is correct.
Score: 1
Accepted Answers:
a. 10 5
1 point
What will be the output of the following C code?
     
#include <stdio.h>

 

int main() {

    int arr[5] = {1, 2, 3, 4, 5};

    int *ptr = arr;

    printf("%d\n", *(ptr + 3));

    return 0;

}

 a. 1
 b. 2
 c. 3
 d. 4
Yes, the answer is correct.
Score: 1
Accepted Answers:
d. 4
1 point
What is the modulus of the complex number z=3+4i ?
 a. 5
 b. 7
 c. 4
 d. 3
Yes, the answer is correct.
Score: 1
Accepted Answers:
a. 5
1 point
What will be the output of the following C++ code snippet?

#include <iostream>

using namespace std;

 

int main() {

    int alpha = 10;

    int *p = &alpha;

    cout << *p << endl;

    return 0;

}


 a. Address of alpha
 b. 10
 c. Garbage value
 d. Compilation Error
Yes, the answer is correct.
Score: 1
Accepted Answers:
b. 10
1 point
In the binomial expansion of (a+b)5, what is the coefficient of the term a3 b2?
 a. 5
 b. 10
 c. 20
 d. 30
Yes, the answer is correct.
Score: 1
Accepted Answers:
b. 10
1 point
Given 3 numbers x, y and z. In order to find the maximum using if-then-else:

if x > y then

    if x > z then

        max = x

    else

        max = z

else

    ________________   #MISSING

        max = y

    else

        max = z


 a. if y > z then
 b. if y < z then
 c. if x > z then
 d. if x < z then
Yes, the answer is correct.
Score: 1
Accepted Answers:
a. if y > z then
1 point
Which of the following statements correctly initializes an array in C? (Please choose All if all are correct)
 a. int arr[5] = {1, 2, 3}
 b. int arr[] = {1, 2, 3}
 c. int arr[5] = {1, 2, 3, 4, 5}
 d. All of these
Yes, the answer is correct.
Score: 1
Accepted Answers:
d. All of these
1 point
What is the output of the following C++ code?

#include <iostream>

using namespace std;

 

void fun(int arr[], int n) {

    for(int i = 0; i < n; i++) {

        arr[i] = arr[i] * arr[i] - arr[i];

    }

}

 

int main() {

    int arr[3] = {1, 2, 3};

    fun(arr, 3);

    for(int i = 0; i < 3; i++) {

        cout << arr[i] << " ";

    }

    cout << endl;

    return 0;

}


 a. 1 4 9
 b. 1 2 3
 c. 0 2 6
 d. 2 4 6
Yes, the answer is correct.
Score: 1
Accepted Answers:
c. 0 2 6
1 point
If the sequence of numbers

	2,6,12,20,30,…

continues in the same pattern, what will be the 7th term in the sequence?
 a. 56
 b. 72
 c. 42
 d. 48
Yes, the answer is correct.
Score: 1
Accepted Answers:
a. 56
1 point
Consider the following C code snippet. What will be the output?

#include <stdio.h>

 

void func(int arr[], int size) {

    for (int i = 0; i < size; i++) {

        arr[i] += 5;

    }

}

 

int main() {

    int arr[] = {1, 2, 3, 4, 5};

    int size = sizeof(arr) / sizeof(arr[0]);

    func(arr, size);

    for (int i = 0; i < size; i++) {

        printf("%d ", arr[i]);

    }

    return 0;

}


 a. 1 2 3 4 5
 b. 6 7 8 9 10
 c. 5 4 3 2 1
 d. 6 7 8 9 11
Yes, the answer is correct.
Score: 1
Accepted Answers:
b. 6 7 8 9 10
1 point
In C++, which of the following operators can be overloaded?
 a. :: (scope resolution operator)
 b. . (member access operator)
 c. + (addition operator)
 d. ?: (ternary operator)
Yes, the answer is correct.
Score: 1
Accepted Answers:
c. + (addition operator)
1 point
Which of the following is true about the new keyword in C++?
 a. It allocates memory on the stack
 b. It allocates memory on the heap
 c. It does not initialize the allocated memory
 d. It can only be used with primitive types
Yes, the answer is correct.
Score: 1
Accepted Answers:
b. It allocates memory on the heap
