# JavaScript Basic Concepts

## Variable’s

4 Ways to Declare a JavaScript Variable:

Using `var`

Using `let`

Using `const`

Using nothing

## Operators

JavaScript has several operators that are used to perform operations on variables and values. Some of the most commonly used operators include:

### Arithmetic Operators

Arithmetic operators are used to perform arithmetic operations on values. The most commonly used arithmetic operators in JavaScript include:

- `+` Addition
- `` Subtraction
- `` Multiplication
- `/` Division
- `%` Modulus (Remainder)

### Assignment Operators

Assignment operators are used to assign values to variables. The most commonly used assignment operators in JavaScript include:

- `=` Simple assignment
- `+=` Add and assign
- `=` Subtract and assign
- `=` Multiply and assign
- `/=` Divide and assign
- `%=` Modulus and assign

### Comparison Operators

Comparison operators are used to compare values. The result of a comparison is a boolean value (`true` or `false`). The most commonly used comparison operators in JavaScript include:

- `==` Equal to
- `!=` Not equal to
- `>` Greater than
- `<` Less than
- `>=` Greater than or equal to
- `<=` Less than or equal to

### Logical Operators

Logical operators are used to test multiple conditions. The most commonly used logical operators in JavaScript include:

- `&&` Logical AND
- `||` Logical OR
- `!` Logical NOT

### Conditional (Ternary) Operator

The conditional operator is a shorthand version of an if-else statement. It is used to assign a value to a variable based on a condition. The conditional operator has the following syntax:

```
condition ? value1 : value2

```

If `condition` is true, `value1` is returned. If `condition` is false, `value2` is returned.

For example:

```
const age = 18;
const status = age >= 18 ? "adult" : "minor";
console.log(status); // prints "adult"

```

In this example, we use the conditional operator to assign the value `"adult"` to the `status` variable if `age` is greater than or equal to `18`. Otherwise, we assign the value `"minor"`.

## Data Type’s

1. String

2. Number

3. Bigint

4. Boolean

5. Undefined

6. Null

7. Symbol

8. Object

## **Primitive Data Types**

Primitive data types are number, string, boolean, NULL, Infinity and symbol. Non-primitive data types is the object. The JavaScript arrays and functions are also objects. 

## **The Non-Primitive Data Types**

The ‘object’ is a non-primitive data type in JavaScript. Arrays and Functions in JavaScript belong to the ‘object’ data type.

Control Statements

Control statements are used to determine the flow of execution in a JavaScript program. Examples of control statements include `if-else` statements, `switch` statements, `for` loops, `while` loops, and `do-while` loops.

## Functions

Functions are reusable blocks of code that perform a specific task. They can be defined using the `function` keyword, followed by the function name, and a set of parentheses that may include parameters. The code to be executed is enclosed in curly braces.

Example:

```
function greet(name) {
  console.log(`Hello, ${name}!`);
}

greet("John"); // prints "Hello, John!"

```

Here's an example of an arrow function in JavaScript:

```
const add = (a, b) => {
  return a + b;
}

console.log(add(2, 3)); // prints 5

```

In this example, we define an arrow function called `add` that takes two parameters `a` and `b`. We use the arrow (`=>`) to separate the parameter list from the function body. The function body contains a single statement that returns the sum of `a` and `b`. We then call the `add` function with the arguments `2` and `3` and print the result to the console.

## Classes and Objects

Classes in JavaScript are a new way of creating objects. They are similar to functions but are more concise and easier to read. To create a class, you use the `class` keyword followed by the name of the class. Inside the class, you define the properties and methods of the object.

Example:

```
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  greet() {
    console.log(`Hello, my name is ${this.name} and I am ${this.age} years old.`);
  }
}

const john = new Person("John", 30);
john.greet(); // prints "Hello, my name is John and I am 30 years old."

```

In this example, we create a `Person` class with a constructor that takes a `name` and `age` parameter. We also define a `greet` method that prints a greeting message using the `name` and `age` properties.

We then create a new `Person` object named `john` using the `new` keyword and passing in the values `"John"` and `30` as arguments to the constructor. Finally, we call the `greet` method on the `john` object to print the greeting message.

## Methods

Methods are functions that are associated with an object. They are defined inside an object and are accessed using the dot (`.`) notation. The `this` keyword is used to refer to the object that the method belongs to.

Example:

```
const person = {
  name: "John",
  age: 30,
  greet() {
    console.log(`Hello, my name is ${this.name} and I am ${this.age} years old.`);
  }
};

person.greet(); // prints "Hello, my name is John and I am 30 years old."

```

In this example, we define a `person` object with a `name` and `age` property, as well as a `greet` method that prints a greeting message using the `name` and `age` properties. We then call the `greet` method on the `person` object to print the greeting message.

JavaScript also has built-in methods that are available on certain types of objects, such as strings and arrays. Some examples of built-in methods include:

- `toUpperCase()` and `toLowerCase()` for strings
- `push()` and `pop()` for arrays
- `toString()` for objects

You can also define your own custom methods on objects.

Example:

```
const calculator = {
  add(a, b) {
    return a + b;
  },
  subtract(a, b) {
    return a - b;
  }
};

console.log(calculator.add(2, 3)); // prints 5
console.log(calculator.subtract(5, 2)); // prints 3

```

In this example, we define a `calculator` object with an `add` method that returns the sum of two numbers, and a `subtract` method that returns the difference between two numbers. We then call the `add` and `subtract` methods on the `calculator` object to perform calculations.
