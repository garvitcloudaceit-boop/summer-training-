## **Conditional Statements - Questions & Answers** 

Day 2 - Programming Fundamentals 

## **1. What is a conditional statement in programming?** 

It is a statement that makes a decision and runs different code depending on whether a condition is true or false. 

## **2. What does an if statement do?** 

It checks a condition and runs a block of code only if that condition is true. 

## **3. What is the purpose of an else block?** 

It runs a block of code when the if condition is false. 

## **4. When is an else block executed?** 

It is executed only when the matching if condition is false. 

## **5. What is a Boolean expression?** 

An expression that evaluates to only one of two values: true or false. 

## **6. Write the syntax of a simple if statement.** 

Basic structure of an if statement: 

```
if (condition) {
    // code runs if condition is true
}
```

## **7. What operator is commonly used to test equality?** 

The double equals operator (==) is used to test if two values are equal. 

## **8. What does the modulus (%) operator return?** 

It returns the remainder after dividing one number by another. 

## **9. How can you check if a number is even?** 

Check if the number divided by 2 leaves a remainder of 0, using number % 2 == 0. 

## **10. How can you check if a number is odd?** 

Check if the number divided by 2 leaves a remainder of 1, using number % 2 != 0. 

## **11. What is the purpose of else-if?** 

It lets you test multiple different conditions, one after another, in the same decision block. 

## **12. What is a nested if statement?** 

An if statement placed inside another if (or else) statement, used to test a condition within a condition. 

## **13. Can an if statement exist without an else?** 

Yes. The else block is optional; an if statement works fine on its own. 

## **14. What is the output when a false condition is tested in an if statement without else?** 

Nothing happens. The program simply skips the if block and continues to the next line of code. 

## **15. What is the role of braces {} in C/C++ conditionals?** 

Braces group multiple statements together so they are treated as a single block to run under the condition. 

## **16. What does > mean?** 

Greater than - checks if the left value is bigger than the right value. 

## **17. What does < mean?** 

Less than - checks if the left value is smaller than the right value. 

## **18. What does >= mean?** 

Greater than or equal to - checks if the left value is bigger than or the same as the right value. 

## **19. What does <= mean?** 

Less than or equal to - checks if the left value is smaller than or the same as the right value. 

## **20. What does != mean?** 

Not equal to - checks if two values are different from each other. 

## **21. What is a switch statement?** 

A conditional structure that compares one value against several possible cases and runs the matching block. 

## **22. What is a case label in a switch statement?** 

It is one possible value that the switch expression is compared against. 

## **23. Why is break used in switch?** 

It stops execution from continuing into the next case once a match has been found and handled. 

## **24. What happens if break is omitted?** 

Execution falls through and continues running the code in the next case as well. 

## **25. What is the default case in switch?** 

It is the block that runs when none of the other case values match. 

## **26. Can switch compare strings in C++?** 

Not directly with plain C-style strings, but it works with enums and integers, and indirectly with std::string using extra logic. 

## **27. Which statement is better for many constant choices: if-else or switch?** 

A switch statement is usually better and cleaner when comparing one variable against many fixed constant values. 

## **28. How do you test whether a value is positive?** 

Check if the value is greater than 0, using value > 0. 

## **29. How do you test whether a value is negative?** 

Check if the value is less than 0, using value < 0. 

## **30. How do you test whether a value is zero?** 

Check if the value is equal to 0, using value == 0. 

## **31. Write a condition to check if age is at least 18.** 

Use a greater-than-or-equal comparison: 

```
if (age >= 18) {
    // eligible
}
```

## **32. Write a condition to check if marks are above 50.** 

Use a greater-than comparison: 

```
if (marks > 50) {
    // passed
}
```

## **33. What is decision making in programming?** 

It is the process of choosing which code to execute based on whether certain conditions are true or false. 

## **34. Can nested if statements have multiple levels?** 

Yes. You can nest if statements as many levels deep as needed, though too many levels can make code hard to read. 

## **35. What is logical AND (&&)?** 

It returns true only when both conditions on either side of it are true. 

## **36. What is logical OR (||)?** 

It returns true when at least one of the two conditions is true. 

## **37. What is logical NOT (!)?** 

It reverses a Boolean value, turning true into false and false into true. 

## **38. How do you check if a year is divisible by 4?** 

Check if the year divided by 4 leaves no remainder, using year % 4 == 0. 

## **39. What is a leap year?** 

A year that has 366 days instead of 365, with an extra day added to February. 

## **40. What is the first condition for a leap year?** 

The year must be evenly divisible by 4. 

## **41. How do you find the largest of two numbers?** 

Compare the two numbers with an if-else statement and return whichever one is greater. 

## **42. How do you find the largest of three numbers?** 

Use nested or chained if-else comparisons to compare all three numbers against each other. 

## **43. What is an if-else-if ladder?** 

A series of if, else if, and else statements chained together to test multiple conditions in order. 

## **44. What is the difference between if and switch?** 

An if statement can test any kind of condition or range, while a switch statement compares one value against a fixed set of exact cases. 

## **45. Can switch use ranges directly?** 

No. A standard switch statement only matches exact values, not ranges of values. 

## **46. What is fall-through in switch?** 

It is when execution continues into the next case block because no break was used to stop it. 

## **47. What data type is usually used for conditions?** 

A Boolean (bool) data type, which holds only true or false. 

## **48. Why are conditional statements important?** 

They allow programs to make decisions and respond differently depending on different situations and inputs. 

## **49. Give one real-life example of a conditional statement.** 

If it is raining, then take an umbrella; otherwise, leave it at home. 

## **50. Name four conditional structures covered.** 

if statement, if-else statement, else-if ladder, and switch statement. 

