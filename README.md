// 1. Comments and Documentation
// This is a single-line comment
/*
This is a
multi-line comment
*/

// 2. Declaration with let
let name = "YourName";
let age = 20;
console.log(name, age);

// 3. Declaration with const
const school = "Your School Name";
const course = "JavaScript";
console.log(school, course);
// school = "something else"; // This would give error (const can't change)

// 4. Checking Data Types
console.log(typeof "Hello");        // string
console.log(typeof 100);            // number
console.log(typeof true);           // boolean
console.log(typeof undefined);      // undefined

// 5. String Data Type
let firstName = "Jack";
let lastName = "Robinson";
let fullName = firstName + " " + lastName;
console.log(fullName);              // Jack Robinson
console.log("Hello".toUpperCase()); // HELLO

// 6. Number Data Type
let num1 = 15;
let num2 = 7;
console.log(num1 + num2);   // 22
console.log(num1 - num2);   // 8
console.log(num1 * num2);    // 30
console.log(num1 / num2);   // ≈2.14

// 7. Boolean Data Type
let isStudent = true;
let hasSubmitted = false;
console.log(isStudent);     // true
console.log(10 > 5);        // true
console.log(5 === 10);       // false

// 8. Undefined vs Null
let nothing;                // undefined (not set yet)
let emptyBox = null;        // intentionally empty
console.log(nothing);       // undefined
console.log(emptyBox);      // null

// 9. Using typeof Operator
console.log(typeof 42);             // "number"
console.log(typeof "Hi");           // "string"
console.log(typeof true);           // "boolean"
console.log(typeof null);           // "object" ← this is a famous JavaScript quirk!
console.log(typeof undefined);      // "undefined"

// 10. Console.log() Practice
console.log("Exercise 1 done");
console.log("Keep going! You got this!");
console.log("Almost finished Day 1");
