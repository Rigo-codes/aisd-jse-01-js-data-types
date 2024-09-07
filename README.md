
# Understanding JavaScript Data Types

## Description 📄

In this lab, you will learn about JavaScript's fundamental data types and how to create variables to store them. By the end, you will be familiar with various data types, including strings, numbers, booleans, undefined, and null. Additionally, you will be introduced to arrays and objects, which allow for more complex data storage and manipulation.

## Expected Project Structure 🏗️

```
DataTypesIntro/
└── index.js
```

# Instructions ✅

## 1. **Create the Project Folder and Files**

- [ ] Create a folder named `DataTypesIntro` to store all your project files.
- [ ] Inside the `DataTypesIntro` folder, create a file named `index.js`. This will be your main JavaScript file.

## 2. **Open Terminal and Navigate to Your Project Folder**

- [ ] Open your terminal or command prompt.
- [ ] Navigate to the `DataTypesIntro` folder using the `cd` command.

```sh
cd path/to/DataTypesIntro
```

## 3. **Understand Variables**

Before diving into data types, it's important to understand variables. A variable is a container that stores data values. In JavaScript, variables are defined using keywords such as `var`, `let`, or `const`. For this lesson, we'll only be using `const` to define our variables. 

### **Why `const`?**

- `const` is used to define a variable that should not change. 
- It helps prevent accidental changes to the variable value later in the program.

## 4. **Strings**

Strings are sequences of characters used to represent text. They are enclosed in single quotes (`'...'`) or double quotes (`"..."`).

- [ ] Open `index.js` and define a string variable:

```js
const greeting = "Hello, World!";
```

**Explanation:**

- `"Hello, World!"` is a string, and `greeting` is the variable that stores this string value.

### **Example: Difference Between String and Number**

A number can also be represented as a string. The difference is that a number string cannot be used in mathematical operations:

```js
const numberString = "42"; // This is a string
const actualNumber = 42; // This is a number

console.log(numberString + 10); // Outputs: 4210 (concatenates as string)
console.log(actualNumber + 10); // Outputs: 52 (performs mathematical addition)
```

## 5. **Numbers**

Numbers represent numeric data and can be either integers or decimals.

- [ ] Define a number variable in your `index.js` file:

```js
const age = 31;
const price = 19.99;
```

**Explanation:**

- `31` and `19.99` are numbers. `age` and `price` are variables storing these number values.

## 6. **Booleans**

Booleans represent logical values and can be either `true` or `false`.

- [ ] Define a boolean variable in your `index.js` file:

```js
const isStudent = true;
const hasGraduated = false;
```

**Explanation:**

- `true` and `false` are boolean values. `isStudent` and `hasGraduated` are variables storing these boolean values.

## 7. **Undefined**

`undefined` is a special data type that represents a variable that has been declared but not assigned a value.

- [ ] Define an undefined variable in your `index.js` file:

```js
let user; // Declared but not assigned
console.log(user); // Outputs: undefined
```

**Explanation:**

- `user` is declared but not given a value, so it is `undefined`.

## 8. **Null**

`null` is a special value that represents "no value" or "nothing." It is intentionally set by the programmer to indicate that a variable has no value.

- [ ] Define a null variable in your `index.js` file:

```js
const currentTask = null;
```

**Explanation:**

- `currentTask` is explicitly set to `null`, indicating it has no value.

## 9. **Arrays and Objects (Complex Data Types)**

Arrays and Objects are more complex data types that allow you to store collections of values.

### **Arrays**

Arrays are ordered collections of other data types. You can store multiple values in a single variable.

- [ ] Define an array in your `index.js` file:

```js
const fruits = ["apple", "banana", "cherry"];
```

**Explanation:**

- `fruits` is an array containing three string elements: "apple", "banana", and "cherry".

### **Objects**

Objects represent more complex data structures where you can store data in key-value pairs.

- [ ] Define an object in your `index.js` file:

```js
const person = {
  name: "Alice",
  age: 30,
  isStudent: false
};
```

**Explanation:**

- `person` is an object with three properties: `name`, `age`, and `isStudent`.

## 10. **Run Your Code**

- [ ] To see your code in action, you can run the `index.js` file in your terminal by using the following command:

```sh
node index.js
```

- Make sure `node.js` is installed on your machine.

## Conclusion 📄

In this lab, you learned about different data types in JavaScript, including strings, numbers, booleans, undefined, and null. You also got a brief introduction to arrays and objects, which are more complex data types. Understanding these fundamental concepts is essential for building a solid foundation in JavaScript programming.
