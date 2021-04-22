# Part 1a

## Var Declaration
1. values added: 20
2. final result: 20

## Let Declaration
1. values added: 20
2. error because `result` is only defined in the if statement

## Const Declaration
1. error because you can't reassign a `const` variable
2. error because you can't reassign a `const` variable

# Part 1b

1. outputs `3` because `prices.length=3` and `i` is incrementing by 1 until it is no longer smaller than `prices.length`
2. outputs `150` because `discountedPrice` retains its value from the last iteration of the for loop which would be `prices[2] * (1-discount)` = 300 * 0.5 = 150
3. outputs `150` because `finalPrice` retains its value from the last iteration of the loop which is 150 = `Math.round(300 * 100)/100`out
4. `[50, 100, 150]` because the function takes a list of prices and applies a discount, returning a list of the discounted prices
5. error because `i` is defined in the for loop and not in the scope
6. error because `discountedPrice` is defined in the for loop and not in the scope
7. outputs `150` because `finalPrice` was defined in the scope
8. `[50, 100, 150]` because it was defined in the proper scope and will function like before even though `discountedPrice` is only in the scope of the loop
9. error because `i` is defined in the for loop and not in the scope
10. prints `3` because that is the length of prices, and it is defined in scope
11. `[50, 100, 150]` because it is defined in scope, and you can push to `const` variables even though they can't be reassigned

## Data Types
12:

A. `student.name`

B. `student["Grad Year"]`

C. `student.greeting()`

D. `student["Favorite Teacher"].name`

E. `student.courseLoad[0]`


## Basic Operators & Type Conversion

13. Arithmetic
  - A: `32` because the 3 is a string and there is a + which can be used for concatinating two strings, so it treats the 2 as a string
  - B: `1` because there is no + sign, so no concatinating, so it treats both as numbers
  - C: `3` because null is valued as 0 for integer arithmetic
  - D: `3null` because it treats it as concatinating two strings
  - E: `4` because true is valued as 1 for integer arithmetic
  - F: `0` because both are valued as 0 for integer arithmetic
  - G: `3undefined` because it treats it as concatinating two strings
  - H: `NaN` because undefined is not a number
14. Comparison
  - A: `true` because it treats the 2 as an integer
  - B: `false` because it is comparing alphabetically
  - C: `true` because it treats them as integers
  - D: `false` because triple equals compares types as well
  - E: `false` because true is 1
  - F: `true` because anything other than 0 becomes true when using Boolean()
15. `==` does not care about type and will convert some expressions while `===` does care about type

## Functions
17. The function will return `[2,4,6]`. The `modifyArray` function takes an array and a function. It then iterates through that array and calls the function on each element, pushing the results into a new array. In this case, `doSomething` returns double the value of the input. Once all the elements have been iterated through, it returns the new array.

## Interval and Timeout

19:
1
3
4
2












