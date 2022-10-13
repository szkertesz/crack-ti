# JavaScript Interview Questions

## Table of Contents

HIGH - 43 questions (~55.8%)
MEDIUM - 27 questions (~35%)
LOW - 7 questions (~9%)

| No.  | Questions                                                                    | Priority |
|------|------------------------------------------------------------------------------|----------|
| 1    | [Data Types](https://github.com/szkertesz/crack-ti/blob/main/questions/js.md#data-types)                                                    |          |
| 1.1  | [What are primitive data types?](https://github.com/szkertesz/crack-ti/blob/main/questions/js.md#primitive-data-types)                                             | HIGH     |
| 1.2  | What are the possible ways to create objects in JavaScript?                  | MEDIUM   |
| 1.3  | What is undefined property?                                                  | HIGH     |
| 1.4  | What is null value?                                                          | HIGH     |
| 1.5  | What is the difference between null and undefined?                           | HIGH     |
| 1.6  | What is the difference between window and document?                          | HIGH     |
| 1.7  | What is isNaN?                                                               | HIGH     |
| 1.8  | What is the difference between let, const and var?                           | HIGH     |
| 1.9  | What are the differences between undeclared and undefined variables?         | HIGH     |
| 1.10 | What are global variables?                                                   | HIGH     |
| 1.11 | What are the problems with global variables?                                 | MEDIUM   |
| 1.12 | What is NaN property?                                                        | HIGH     |
| 1.13 | What are classes in ES6?                                                     | HIGH     |
| 1.14 | How do you check whether a string contains a substring?                      | MEDIUM   |
| 1.15 | How do you check if a key exists in an object?                               | MEDIUM   |
| 1.16 | How do you copy properties from one object to other?                         | HIGH     |
| 1.17 | What is a proxy object?                                                      | LOW      |
| 1.18 | What is the main difference between Object.values and Object.entries method? | MEDIUM   |
| 1.19 | How can you get the list of keys of any object?                              | MEDIUM   |
| 1.20 | How do you create an object with prototype?                                  | LOW      |
| 1.21 | What is a WeakSet?                                                           | MEDIUM   |
| 1.22 | What are the differences between WeakSet and Set?                            | MEDIUM   |
| 1.23 | What is a WeakMap?                                                           | MEDIUM   |
| 1.24 | What are the differences between WeakMap and Map?                            | MEDIUM   |
| 1.25 | What is Hoisting?                                                            | HIGH     |
| 1.26 | How do you assign default values to variables?                               | HIGH     |
| 2    | Context, Scope proto and Prototype                                           |          |
| 2.1  | What is the difference between Call, Apply and Bind?                         | HIGH     |
| 2.2  | What is scope in javascript?                                                 | HIGH     |
| 2.3  | What is the difference between proto and prototype?                          | LOW      |
| 2.4  | What is prototype chain?                                                     | HIGH     |
| 3    | JSON                                                                         |          |
| 3.1  | What is JSON and its common operations?                                      | HIGH     |
| 3.2  | How do you parse JSON string?                                                | HIGH     |
| 3.3  | Why do you need JSON?                                                        | MEDIUM   |
| 3.4  | What is the purpose JSON stringify?                                          | HIGH     |
| 3.5  | How do you define JSON arrays?                                               | LOW      |
| 4    | Array methods                                                                |          |
| 4.1  | What is the purpose of the array slice method?                               | MEDIUM   |
| 4.2  | What is the purpose of the array splice method?                              | MEDIUM   |   
| 4.3  | What array methods do you know?                                              | HIGH     |
| 4.4  | What is the difference between Array.forEach() and Array.map()?              | HIGH     |
| 5    | Functions                                                                    |          |
| 5.1  | What are lambda or arrow functions?                                          | HIGH     |
| 5.2  | What is a first class function?                                              | MEDIUM   |
| 5.3  | What is a first order function?                                              | MEDIUM   |
| 5.4  | What is a higher order function?                                             | MEDIUM   |
| 5.5  | What is a unary function?                                                    | MEDIUM   |
| 5.6  | What is the currying function?                                               | MEDIUM   |
| 5.7  | What is a pure function?                                                     | HIGH     |
| 5.8  | What are closures?                                                           | HIGH     |
| 5.9  | What is IIFE(Immediately Invoked Function Expression)?                       | HIGH     |
| 5.10 | What is a callback function?                                                 | HIGH     |
| 5.11 | What is an anonymous function?                                               | MEDIUM   |
| 6    | Async JavaScript                                                             |          |
| 6.1  | What is a promise?                                                           | HIGH     |
| 6.2  | Why do you need a promise?                                                   | HIGH     |
| 6.3  | What are the three states of promise?                                        | HIGH     |
| 6.4  | Why do we need callbacks?                                                    | HIGH     |
| 6.5  | What is a callback hell?                                                     | HIGH     |
| 6.6  | What is promise chaining?                                                    | HIGH     |
| 6.7  | What is promise.all?                                                         | MEDIUM   |
| 6.8  | What is the purpose of race method in promise?                               | MEDIUM   |
| 6.9  | What is the use of setTimeout?                                               | HIGH     |
| 6.10 | What is the use of setInterval?                                              | HIGH     |
| 6.11 | What is an event loop?                                                       | HIGH     |
| 6.12 | What is call stack?                                                          | HIGH     |
| 7    | Common                                                                       |          |
| 7.1  | What is a strict mode in javascript?                                         | MEDIUM   | 
| 7.2  | What are PWAs?                                                               | MEDIUM   |
| 7.3  | How do you validate an email in javascript?                                  | HIGH     |
| 7.4  | How do you get the current url with javascript?                              | MEDIUM   |
| 7.5  | What is tree shaking?                                                        | LOW      |
| 7.6  | What is memoization?                                                         | MEDIUM   |
| 7.7  | What are modules?                                                            | HIGH     |
| 7.8  | Why do you need modules?                                                     | HIGH     |
| 7.9  | How do you detect a mobile browser?                                          | LOW      |
| 7.10 | How do you detect javascript disabled in the page?                           | LOW      |
| 7.11 | What is a rest parameter?                                                    | HIGH     |
| 7.12 | What is a spread operator?                                                   | HIGH     |
| 7.13 | How do you encode an URL?                                                    | MEDIUM   |
| 7.14 | How do you decode an URL?                                                    | MEDIUM   |
| 7.15 | What is nodejs?                                                              | HIGH     |

### Data Types

#### What are primitive data types?

