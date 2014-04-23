# Functions

## `exercise01`

try to understand what happens in here:

```js
function greets () {
 console.log('Hello!');
 greets = function () {
   console.log('Bye!');
   return greets;
 };
 return greets;
}

greets();

greets()();

greets()()();
```

```js
function greets () {
 console.log('Hello!');
 var greets = function () {
   console.log('Bye!');
   return greets;
 };
 return greets;
}

greets();

greets()();

greets()()();
```

## `exercise02`

write a script containing the function `identity(n)`  
that returns the `n` rows by `n` columns identity matrix

## `exercise03`

write a script containing the function `fibonacci(i)`   
that returns the i-th element of the Fibonacci's serie (apply memoization pattern)

