# Operators
## Comparison Operators 
### Evaluating Conditions
- you can evaluate a situation by comparing one value in the script to what you expect it might be.
- the result will be a Boolean: ```true``` or ```false```
  - usally result in true/false
- programmers refer to the testing or checking of a condition as **evaluating** the condition
- exceptions to true/false:
  - every value can be treated as ```true``` or ```false``` even if it's not a Boolean ```true``` or ```false``` value
  - in short-circuit evaluation, a condition might not need to run 

---

```==``` - equal to. compares two value numbers to check if they are the same. usually preferable to use the **strict** method. 

```===``` - **strict** equal to. compares two value numbers to check if both the *data type* and *value* are the same. 

```!=``` - not equal to. compares two value numbers to check if they are not the same. usually preferable to use the **strict** method.

```!==``` - **strict** not equal to. compares two value numbers to check if both the *data type* and *value* are not the same.

```>``` - greater than

```<``` - less than

```>=``` - greater than or equal to

```<=``` - less than or equal to 

---

## Logical Operators
- comparison operators usually return single values of true or false.
- logical operators allow you to compare the results of more than one comparison operator.

--- 
```&&``` - logical and. tests more than one condition. 
- if both expressions are ```true``` then expression returns true. 
- if even just one expression is ```false``` then it will return false.

```||``` - logical or. tests at least one condition. 
- if **either** expression is ```true``` then the expression is true.
- if both expressions are ```false``` then the expression is false.

```!``` - logical not. takes a single Boolean value and inverts it.
- if the statement was ```false``` (without the ! before it), it would return ```true```
- if it was ```true```, the statement would return ```false```. 
---

### Expression Example:
on this one line of code there are **three expressions**
- each resolve ```true``` or ```false```
- both exp 1 and exp 2 both use comparison operators.
    - both return false
- third uses a logical operator 
- both logical and operator check to see if both expressions on either side of it return true
    - they don't so it's ```false```

```((5 < 2) && (2 >= 3))```
- ```(5 < 2)``` - exp 1
- ```&&``` - logical operator
- ```(2 >= 3)``` - exp 2

# Loops 
- checks a condition.
- if returns true a code block will run
    - then the condition will be checked again, and again as long as it's true
- repeats until the condition turns false

**super basic example of a loop**

---
```
           initialization  
                 |             
                 |             
     — — — — — condition — — — — — —       
    | < [if false]  | < [if true]   |
    |               |               |
    |               |               |
    |              loop _ _ _ _ _ _ |  
    |
  stop 
``` 
---

There are there are three common types of loop:

```for``` - run a code for a specific number of times
- most common loop
- condition is usually a counter that counts how many time the loop should run

```while``` - continuous loop
- condition can be comething other than a counter 
- will continually loop for as long as the condition is ```true```. 

```do while``` - similar to ```while``` but will always run the statements inside the curly braces at least once. even if the condition evaluates to ```false```.

### For
- uses a counter as a condition
- instructs the code to run a specific number of times 

[<==back](README.md) 









