# Built-ins

## `exercise01`

### `exercise01a`

write a function that pushes into an array the first `n` natural numbers

### `exercise01b`

filter out odd number and return the even ones

### `exercise01c`

double each even number obtained

### `exercise01d`

return only numbers divisible by `4`

### `exercise01e`

sum all the remaining numbers

## `exercise02`

### `exercise02a`

write a function that pushes into an array `n` random integer numbers

### `exercise02b`

filter even numbers and return the odd ones

### `exercise02c`

sort obtained numbers from the smallest to the largest

## `exercise03`

### `exercise03a`

write a function that given a word return it capitalized

### `exercise03b`

write a function that capitalize each word of the following text:

    "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## `exercise04`

write a function `select(data, key, values)` that given an array of objects data, a string key and an array of values values, returns the array of objects where the property key is equal to one of the values in values. For example:

    var data = [
      {id:'01', name:'duffy'},
      {id:'02', name:'michey'},
      {id:'03', name:'donald'},
      {id:'04', name:'goofy'},
      {id:'05', name:'minnie'},
      {id:'06', name:'scrooge'}
    ];
    var key = 'name';
    var values = ['goofy', 'scrooge'];

    select(data, key, values)
    // [ { id:'04', name:'goofy' }, { id:'06', name:'scrooge' } ]



## `exercise05`

write a function that randomizes `3` numbers in range `(0.. 100)` and prints the largest one

## `exercise06`

write a function that randomizes a number in range `(0..100)`, then prints all the even numbers from 0 to the randomized

## `exercise07`

werite a function that randomizes a number in range `(0..100)`, then prints all the odd numbers from 40 to that one. If the number was smaller than 40 nothing should be printed

## `exercise08`

write a funciton that randomizes a number in range `(0..100)`, then prints all the odd numbers from 40 to that one. If the number was smaller than 40, print all the numbers down to the randomized one (i.e. if the result was 37, you should print: 40, 39, 38, 37)

## `exercise09`

write a funciton that randomizes a number n in range `0..100`. Now randomizes `n` more numbers in that range, printing the largest of them

## `exercise10`

write a funciton that randomizes a number in range `(1000..9999)` and calculate the sum of its digits. For instance, if the randomized number was 1049, program should print 14


## `exercise11`

write a funciton that randomizes a number in range `(1000..9999)` and calculate the sum of its digits repeatedly until you reach one digit only. For instance, if the randomized number was 1049, program should print 5

## `exercise12`

write a funciton that randomizes two numbers and prints the smallest number that is greater than one, such that both numbers are divided by it with no remainder. For instance, for 9 and 6 you should print 3. If there isn't one a proper note should be printed

## `exercise13`

write a funciton that randomizes two numbers and prints their least common multiplication of them. (use [lcm](http://en.wikipedia.org/wiki/Least_common_multiple) for details)

## `exercise14`

write a funciton that randomizes two numbers and prints their average and standard deviation
