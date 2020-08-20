# Programming
- script is a series of instructions that the computer can follow in order to achieve a goal
- each time the script runs, it might only use a subset of all instructions
- computers approach tasks differently than humans. instructions must let the computer sold the task programmatically
- to approach writing a script, break down goal into series of tasks and then work out each step needed (like a flowchart)

## Expressions
1. Assign a value to a variable

``` var color = 'beige';```

2. Use two or more values to return a single value

``` var area = 3 * 2```

## Operators
- expressions rely on operators
- allow programmers to create a single value fom one or ore values 

### Arithmetic Operators
- JS contains the following mathmatical operators, used with numbers
- must order specifically how you want things to go or else they might calculate or combine differently

**The only string operator is the + symbol. It joins the strings on either side**
- joining multiple strings to become a new string is called *concatenation*
- ex. numbers in quotations = string
- nan = not a number 

# Functions
- let's you group a series of statements together to perform a specific task
- if different parts of a script repeat the same task, you can reuse the function (don't have to repeat the same set of statements)

## Declaring a function
1. give it a name
2. write statements needed to achieve its task inside the curly braces
**this is called a function declaration**

function example:
```
function sayHello() {
    document.write('hello!');
}
```

- what happens in a function stays in a function
- function won't show up unless you invoke it

invoke example:
```
sayHello();
```

-  in order to get this to work, we need to get the return value of the function

```

[<==back](README.md) 