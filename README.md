## Lab 3 - Git & Github 
### Task 1: FizzBuzzBang
Design a class FizzyPrinter with printFizzy method. The method should at least take an
integer n as parameter and return a string. The logic should be:
1. If n is divisible by 3, return “Fizz”.
2. If n is divisible by 5, return “Buzz”.
3. If n is divisible by 7, return “Bang”.
4. If n is divisible by 3 and 5, return “Fizzbuzz”.
5. If n is divisible by all three number, return “Fizzbuzzbang”.
6. Otherwise, return "Boom".
7. Return string can in all uppercase if user wants.
   Write at least 3 unit tests to validate each of the cases.
### Task 2: MinStack
You need to create a class named MinStack that represents a last-in-first-out (LIFO) data
structure with following properties:
1. It has push(int) and pop() operations that work the same way as a normal stack.
2. In addition to that, it also has a min() operation that returns the minimum value in the
   current stack.

Constraints:

The min() operation should operate at constant complexity, O(1). Which means you cannot
use a loop or recursion to find the minimum value.

Test Cases:

Test Case 1:
- Push 3, 2, 5, 1.
- Assert min = 1 (Expected Output)

Test Case 2:
- Push 3, 2, 5, 1.
- Pop
- Assert min = 2 (Expected Output)
Test Case 3:
- Push 1, 2, 3, 4.
- Assert min = 1 (Expected Output)

Hints, you can use the built-in stack class if you want.
