# JavaScript Interview Questions

## Table of Contents

HIGH - 43 questions (~55.8%)
MEDIUM - 27 questions (~35%)
LOW - 7 questions (~9%)

| No.  | Questions                                                                    | Priority |
|------|------------------------------------------------------------------------------|----------|
| 1    | [Data Types](https://github.com/szkertesz/crack-ti/blob/main/questions/js.md#data-types)                                                    |          |
| 1.1  | [What are primitive data types?](https://github.com/szkertesz/crack-ti/blob/main/questions/js.md#primitive-data-types)                                             | HIGH     |
| 1.2  | [What are the possible ways to create objects in JavaScript?](What-are-the-possible-ways-to-create-objects-in-JavaScript)                  | MEDIUM   |
| 1.3  | [What is undefined property?](What is undefined property?)                                                  | HIGH     |
| 1.4  | [What is null value?](What is null value?)                                                          | HIGH     |
| 1.5  | [What is the difference between null and undefined?](What is the difference between null and undefined?)                           | HIGH     |
| 1.6  | [What is the difference between window and document?](What is the difference between window and document?)                          | HIGH     |
| 1.7  | [What is isNaN?](What is isNaN?)                                                               | HIGH     |
| 1.8  | [What is the difference between let, const and var?](What is the difference between let, const and var?)                           | HIGH     |
| 1.9  | [What are the differences between undeclared and undefined variables?](What are the differences between undeclared and undefined variables?)         | HIGH     |
| 1.10 | [What are global variables?](What are global variables?)                                                   | HIGH     |
| 1.11 | [What are the problems with global variables?](What are the problems with global variables?)                                 | MEDIUM   |
| 1.12 | [What is NaN property?](What is NaN property?)                                                        | HIGH     |
| 1.13 | [What are classes in ES6?](What are classes in ES6?)                                                     | HIGH     |
| 1.14 | [How do you check whether a string contains a substring?](How do you check whether a string contains a substring?)                      | MEDIUM   |
| 1.15 | [How do you check if a key exists in an object?](How do you check if a key exists in an object?)                               | MEDIUM   |
| 1.16 | [How do you copy properties from one object to other?](How do you copy properties from one object to other?)                         | HIGH     |
| 1.17 | [What is a proxy object?](What is a proxy object?)                                                      | LOW      |
| 1.18 | [What is the main difference between Object.values and Object.entries method?](What is the main difference between Object.values and Object.entries method?) | MEDIUM   |
| 1.19 | [How can you get the list of keys of any object?](How can you get the list of keys of any object?)                              | MEDIUM   |
| 1.20 | [How do you create an object with prototype?](How do you create an object with prototype?)                                  | LOW      |
| 1.21 | [What is a WeakSet?](What is a WeakSet?)                                                           | MEDIUM   |
| 1.22 | [What are the differences between WeakSet and Set?](What are the differences between WeakSet and Set?)                            | MEDIUM   |
| 1.23 | [What is a WeakMap?](What is a WeakMap?)                                                           | MEDIUM   |
| 1.24 | [What are the differences between WeakMap and Map?](What are the differences between WeakMap and Map?)                            | MEDIUM   |
| 1.25 | [What is Hoisting?](What is Hoisting?)                                                            | HIGH     |
| 1.26 | [How do you assign default values to variables?](How do you assign default values to variables?)                               | HIGH     |
| 2    | [Context, Scope proto and Prototype ](Context, Scope proto and Prototype )                                          | *        |
| 2.1  | [What is the difference between Call, Apply and Bind?](What is the difference between Call, Apply and Bind?)                         | HIGH     |
| 2.2  | [What is scope in javascript?](What is scope in javascript?)                                                 | HIGH     |
| 2.3  | [What is the difference between proto and prototype?](What is the difference between proto and prototype?)                          | LOW      |
| 2.4  | [What is prototype chain?](What is prototype chain?)                                                     | HIGH     |
| 3    | [JSON ](JSON )                                                                        | *        |
| 3.1  | [What is JSON and its common operations?](What is JSON and its common operations?)                                      | HIGH     |
| 3.2  | [How do you parse JSON string?](How do you parse JSON string?)                                                | HIGH     |
| 3.3  | [Why do you need JSON?](Why do you need JSON?)                                                        | MEDIUM   |
| 3.4  | [What is the purpose JSON stringify?](What is the purpose JSON stringify?)                                          | HIGH     |
| 3.5  | [How do you define JSON arrays?](How do you define JSON arrays?)                                               | LOW      |
| 4    | [Array methods ](Array methods )                                                               | *        |
| 4.1  | [What is the purpose of the array slice method?](What is the purpose of the array slice method?)                               | MEDIUM   |
| 4.2  | [What is the purpose of the array splice method?](What is the purpose of the array splice method?)                              | MEDIUM   |
| 4.3  | [What array methods do you know?](What array methods do you know?)                                              | HIGH     |
| 4.4  | [What is the difference between Array.forEach() and Array.map()? ](What is the difference between Array.forEach() and Array.map()? )             | HIGH     |
| 5    | [Functions ](Functions )                                                                   | *        |
| 5.1  | [What are lambda or arrow functions?](What are lambda or arrow functions?)                                          | HIGH     |
| 5.2  | [What is a first class function?](What is a first class function?)                                              | MEDIUM   |
| 5.3  | [What is a first order function?](What is a first order function?)                                              | MEDIUM   |
| 5.4  | [What is a higher order function?](What is a higher order function?)                                             | MEDIUM   |
| 5.5  | [What is a unary function?](What is a unary function?)                                                    | MEDIUM   |
| 5.6  | [What is the currying function?](What is the currying function?)                                               | MEDIUM   |
| 5.7  | [What is a pure function?](What is a pure function?)                                                     | HIGH     |
| 5.8  | [What are closures?](What are closures?)                                                           | HIGH     |
| 5.9  | [What is IIFE(Immediately Invoked Function Expression)? ](What is IIFE(Immediately Invoked Function Expression)? )                      | HIGH     |
| 5.10 | [What is a callback function?](What is a callback function?)                                                 | HIGH     |
| 5.11 | [What is an anonymous function?](What is an anonymous function?)                                               | MEDIUM   |
| 6    | [Async JavaScript ](Async JavaScript )                                                            | *        |
| 6.1  | [What is a promise?](What is a promise?)                                                           | HIGH     |
| 6.2  | [Why do you need a promise?](Why do you need a promise?)                                                   | HIGH     |
| 6.3  | [What are the three states of promise?](What are the three states of promise?)                                        | HIGH     |
| 6.4  | [Why do we need callbacks?](Why do we need callbacks?)                                                    | HIGH     |
| 6.5  | [What is a callback hell?](What is a callback hell?)                                                     | HIGH     |
| 6.6  | [What is promise chaining?](What is promise chaining?)                                                    | HIGH     |
| 6.7  | [What is promise.all?](What is promise.all?)                                                         | MEDIUM   |
| 6.8  | [What is the purpose of race method in promise?](What is the purpose of race method in promise?)                               | MEDIUM   |
| 6.9  | [What is the use of setTimeout?](What is the use of setTimeout?)                                               | HIGH     |
| 6.10 | [What is the use of setInterval?](What is the use of setInterval?)                                              | HIGH     |
| 6.11 | [What is an event loop?](What is an event loop?)                                                       | HIGH     |
| 6.12 | [What is call stack?](What is call stack?)                                                          | HIGH     |
| 7    | [Common ](Common )                                                                      | *        |
| 7.1  | [What is a strict mode in javascript?](What is a strict mode in javascript?)                                         | MEDIUM   |
| 7.2  | [What are PWAs?](What are PWAs?)                                                               | MEDIUM   |
| 7.3  | [How do you validate an email in javascript?](How do you validate an email in javascript?)                                  | HIGH     |
| 7.4  | [How do you get the current url with javascript?](How do you get the current url with javascript?)                              | MEDIUM   |
| 7.5  | [What is tree shaking?](What is tree shaking?)                                                        | LOW      |
| 7.6  | [What is memoization?](What is memoization?)                                                         | MEDIUM   |
| 7.7  | [What are modules?](What are modules?)                                                            | HIGH     |
| 7.8  | [Why do you need modules?](Why do you need modules?)                                                     | HIGH     |
| 7.9  | [How do you detect a mobile browser?](How do you detect a mobile browser?)                                          | LOW      |
| 7.10 | [How do you detect javascript disabled in the page?](How do you detect javascript disabled in the page?)                           | LOW      |
| 7.11 | [What is a rest parameter?](What is a rest parameter?)                                                    | HIGH     |
| 7.12 | [What is a spread operator?](What is a spread operator?)                                                   | HIGH     |
| 7.13 | [How do you encode an URL?](How do you encode an URL?)                                                    | MEDIUM   |
| 7.14 | [How do you decode an URL?](How do you decode an URL?)                                                    | MEDIUM   |
| 7.15 | [What is nodejs?](What is nodejs?)                                                              | HIGH     |

### Data Types

#### What are primitive data types?

#### What are the possible ways to create objects in JavaScript?
#### What is undefined property?
#### What is null value?
#### What is the difference between null and undefined?
#### What is the difference between window and document?
#### What is isNaN?
#### What is the difference between let, const and var?
#### What are the differences between undeclared and undefined variables?
#### What are global variables?
#### What are the problems with global variables?
#### What is NaN property?
#### What are classes in ES6?
#### How do you check whether a string contains a substring?
#### How do you check if a key exists in an object?
#### How do you copy properties from one object to other?
#### What is a proxy object?
#### What is the main difference between Object.values and Object.entries method?
#### How can you get the list of keys of any object?
#### How do you create an object with prototype?
#### What is a WeakSet?
#### What are the differences between WeakSet and Set?
#### What is a WeakMap?
#### What are the differences between WeakMap and Map?
#### What is Hoisting?
#### How do you assign default values to variables?
#### Context, Scope proto and Prototype 
#### What is the difference between Call, Apply and Bind?
#### What is scope in javascript?
#### What is the difference between proto and prototype?
#### What is prototype chain?
### JSON 
#### What is JSON and its common operations?
#### How do you parse JSON string?
#### Why do you need JSON?
#### What is the purpose JSON stringify?
#### How do you define JSON arrays?
### Array methods 
#### What is the purpose of the array slice method?
#### What is the purpose of the array splice method?
#### What array methods do you know?
#### What is the difference between Array.forEach() and Array.map()? 
### Functions 
#### What are lambda or arrow functions?
#### What is a first class function?
#### What is a first order function?
#### What is a higher order function?
#### What is a unary function?
#### What is the currying function?
#### What is a pure function?
#### What are closures?
#### What is IIFE(Immediately Invoked Function Expression)? 
#### What is a callback function?
#### What is an anonymous function?
### Async JavaScript 
#### What is a promise?
#### Why do you need a promise?
#### What are the three states of promise?
#### Why do we need callbacks?
#### What is a callback hell?
#### What is promise chaining?
#### What is promise.all?
#### What is the purpose of race method in promise?
#### What is the use of setTimeout?
#### What is the use of setInterval?
#### What is an event loop?
#### What is call stack?
### Common 
#### What is a strict mode in javascript?
#### What are PWAs?
#### How do you validate an email in javascript?
#### How do you get the current url with javascript?
#### What is tree shaking?
#### What is memoization?
#### What are modules?
#### Why do you need modules?
#### How do you detect a mobile browser?
#### How do you detect javascript disabled in the page?
#### What is a rest parameter?
#### What is a spread operator?
#### How do you encode an URL?
#### How do you decode an URL?
#### What is nodejs?