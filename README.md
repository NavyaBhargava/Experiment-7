# Python While Loop Programs — Theory README

## 1. While Loop

A **while loop** is a control flow statement used to execute a block of statements repeatedly as long as a given condition remains true. It is generally used when the number of iterations is not known in advance. The loop checks the condition before each iteration, and if the condition becomes false, the loop stops.

## ALGORITHM
1. Start
2. Initialize the control variable
3. Check the condition
4. If the condition is true, execute the statements
5. Update the control variable
6. Repeat steps 3–5 until the condition becomes false
7. Stop

---

## 2. Printing Numbers Using a While Loop

A while loop can be used to print numbers in sequence. The loop begins with an initial value and keeps increasing it until it reaches a specified limit. This demonstrates how loops help automate repetitive tasks.

## ALGORITHM
1. Start
2. Initialize a counter with a starting value
3. Check if the counter is within the limit
4. Print the counter value
5. Increase the counter
6. Repeat until the limit is reached
7. Stop
---

## 3. Factorial of a Number

The factorial of a number is the product of all positive integers less than or equal to that number. A while loop repeatedly multiplies numbers in descending order until it reaches one. The concept demonstrates accumulation, where a result variable stores the ongoing product.

## ALGORITHM
1. Start
2. Input a number
3. Initialize factorial as 1
4. Multiply factorial by the number
5. Decrease the number by 1
6. Repeat steps 4–5 until the number becomes 0
7. Display the factorial
8. Stop
---

## 4. Fibonacci Series

The Fibonacci sequence is a series in which each number is the sum of the two preceding numbers. A while loop helps generate this sequence by updating values step by step. It is commonly used to understand variable updates and sequence generation.

## ALGORITHM
1. Start
2. Input number of terms
3. Initialize first two values
4. Print the first value
5. Find next term by adding previous two values
6. Update variables
7. Repeat until required terms are generated
8. Stop
---

## 5. Fibonacci Series with a Limit

Instead of generating a fixed number of terms, a while loop can also generate numbers until a certain limit is reached. The loop continues as long as the generated value does not exceed the given limit.

## ALGORITHM
1. Start
2. Input limit value
3. Initialize first two values
4. Print value if within limit
5. Generate next term
6. Repeat while value is within limit
7. Stop
---

## 6. Reversing a Number

Reversing a number involves extracting digits one by one and building a new number in reverse order. A while loop repeatedly separates the last digit and adds it to a new variable that stores the reversed result.

## ALGORITHM
1. Start
2. Input a number
3. Initialize reverse as 0
4. Extract last digit
5. Add digit to reverse
6. Remove last digit from number
7. Repeat until number becomes 0
8. Display reversed number
9. Stop
---

## 7. Palindrome Number

A palindrome number is a number that remains the same when reversed. The process involves reversing the original number and comparing it with the initial value. If both values are equal, the number is a palindrome.

---

## 8. Palindrome String

A string palindrome checks whether a word reads the same from left to right and right to left. This is done by comparing characters from the beginning and the end moving toward the center. If all characters match, the string is considered a palindrome.

## ALGORITHM
1. Start
2. Input a number
3. Store original number
4. Reverse the number
5. Compare reversed number with original
6. If equal, it is a palindrome
7. Otherwise, not a palindrome
8. Stop
# Palindrome String
1. Start
2. Input a string
3. Set pointers at start and end
4. Compare characters
5. Move pointers toward center
6. If mismatch occurs, not a palindrome
7. If all match, it is a palindrome
8. Stop
---

## 9. Counting Digits in a Number

The number of digits in an integer can be determined by repeatedly removing the last digit until no digits remain. Each removal increases a counter that represents the total digit count.

## ALGORITHM
1. Start
2. Input a number
3. Initialize count as 0
4. Remove last digit
5. Increase count
6. Repeat until number becomes 0
7. Display count
8. Stop
---

## 10. Searching for elements in a list 

The **continue** statement is used inside loops to skip the remaining statements in the current iteration and move directly to the next iteration. It is useful when certain conditions require ignoring specific values while continuing the loop execution.

## ALGORITHM
1. Start
2. Initialize loop variable
3. Check loop condition
4. If condition for skipping occurs, move to next iteration
5. Otherwise, execute remaining statements
6. Repeat until condition becomes false
7. Stop
---

### Conclusion - We learnt how to implement while loop in Python 
