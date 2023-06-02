# Last-Minute-Javascript

## Reference of some websites
[ProTechStack](https://protechstack.com/interview/javascript-interview-questions) \
[ProTechStack](https://protechstack.com/interview/javascript-interview-questions)

## Types in Javascript
    Number = 1, 2, 3, 4, 5, 6, 7, 8, 9, 0
    String = "Hello World"
    Boolean = true, false
    Undefined = undefined
    Null = null
    Object = {key: value}
    Array = [1, 2, 3, 4, 5]

## Scope in Javascript
    Global Scope = Globally declared variables (eg: outside a function)
    Local Scope = Locally declared variables (eg: inside a function)
    Block Scope = Variables declared inside a block (eg: inside a for loop)

## Let, Var, Const
    Var = reassignable, global, local
    Let = reassignable, global, local, block
    Const = cant be reassigned, global, local, block

## =, ==, ===
    = is assignment operator (eg: assigns a value)
    == is equality operator (eg: checks if the value is equal)
    === is strict equality operator (eg: checks if the value and type are equal)

## Hoisting
    Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution.

    function doSomething() {
        x = 33;
        console.log(x);
        var x;
    } 

    // To avoid hoisting, you can run javascript in strict mode by using “use strict” on top of the code:
    "use strict";
    x = 23; // Gives an error since 'x' is not declared
    var x;

## Methods in Javacsript
### CharAt()
	It returns the character at the specified index.
### Concat()
	It joins two or more strings.
### forEach()
	It calls a function for each element in the array.
### indexOf()
	It returns the index within the calling String object of the first occurrence of the specified value.
### length()
	It returns the length of the string.
### pop()
	It removes the last element from an array and returns that element.
### push()
	It adds one or more elements to the end of an array and returns the new length of the array.
### reverse()
	It reverses the order of the elements of an array