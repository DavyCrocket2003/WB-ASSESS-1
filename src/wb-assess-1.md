# Unit 1 Assessment: Written Questions

> To select an answer for the multiple choice questions, put an `x` inside the square brackets (`[ ]`) like this:
> ```md
> - [x] This is the answer!
> ```
>
> **Pro tip:** You might find it easier to read the assessment through VS Code's Markdown Preview. To view the preview for this document, open the Command Palette (<kbd>Cmd+Shift-P</kbd> or <kbd>Ctrl+Shift-P</kbd>) and run `Markdown: Open Preview to the Side`.

## A. Multiple choice questions

### A.1. Which statement is true?

Which statement is true about JavaScript?

- [ ] **A.** JavaScript is case insensitive, so `true` is the same as `True`.
- [ ] **B.** JavaScript ignores whitespace characters like spaces and newline characters.
- [ ] **C.** JavaScript requires you to end all statements with a semicolon (`;`).
- [ ] **D.** All of the above are true.
- [x] **E.** None of the above are true.

### A.2. Turn `sum` to `2`.

Assume you've initialized a variable, `sum`, like so:

```js
let sum = 1;
```

Which of these lines of code will cause `sum` to have a value of `2`? You can select more than one
answer.

- [ ] **A.** `sum++`
- [ ] **B.** `sum += 1`
- [ ] **C.** `sum = sum + 1`
- [x] **D.** All of the above
- [ ] **E.** Some of the above

### A.3. What's the output?

What's the output of the program below?

```js
const result = 1 < 100 || 'hello' === 'hi';
console.log(result);
```

- [x] **A.** `true`
- [ ] **B.** `false`
- [ ] **C.** `undefined`
- [ ] **D.** N/A because the code has an error

### A.4. What's the output?

What's the output of the program below?

```js

```

- [ ] **A.** `yay!`
- [x] **B.** `no :(`
- [ ] **C.** An empty line
- [ ] **D.** N/A because the code has an error

### A.5. Fill in the blank

The code below is incomplete. There's a blank space inside the `for` loop:

```js
const fruits = ['apple', 'berry', 'cherry'];
for (______) {
  console.log(fruit);
}
```

Fill in the blank---select the code that will produce the following output:

```text
apple
berry
cherry
```

- [ ] **A.** `const fruit in fruits`
- [x] **B.** `const fruit of fruits`
- [ ] **C.** `let fruit = 0; fruit < fruits.length; fruit++`
- [ ] **D.** None of the above

### A.6. What will happen?

What will happen when we run the program below? If there's more than one option that seems
correct, pick the one you think is **most accurate**.

```js
function makeWordArray(phrase) {
  return phrase.split(' ');
}
```

- [ ] **A.** Nothing happens because the program errors out.
- [ ] **B.** It defines a function called `makeWordArray` and converts `phrase` into an array of words.
- [ ] **C.** It defines a function called `makeWordArray` and outputs a word array.
- [x] **D.** It defines a function called `makeWordArray` but nothing else happens.

### A.7. Identify the error

Which statement best describes the error below?

```js
console.log'hi';
// expected output:
// hi
```

- [x] **A.** The code causes an error because there should be parentheses around `'hi'`.
- [ ] **B.** The code causes an error because `console.log` isn't a function.
- [ ] **C.** The code causes an error because the code will run but it won't output anything.
- [ ] **D.** There is no error; the code generates the expected output.

### A.8. Identify the error

Which statement best describes the error below?

```js
const fruits = ['apple', 'berry', 'cherry'];
console.log(fruits[fruits.indexOf('apple')]);
// expected output:
// apple
```

- [ ] **A.** The code causes an error because `fruits[fruits.indexOf('apple')]` isn't valid
  JavaScript syntax.
- [ ] **B.** The code causes an error because `fruits.indexOf('apple')` doesn't return a valid
  index number.
- [ ] **C.** The code causes an error because it outputs `0` instead of the expected output.
- [x] **D.** There is no error; the code generates the expected output.

### A.9. Identify the error

Which statement best describes the error below?

```js
const words = ['js', 'html', 'css'];
for (const w of words) {
  console.log(words.toUpperCase());
}
// expected output:
// JS
// HTML
// CSS
```

- [ ] **A.** The code causes an error because `w` needs to be a `let` variable.
- [x] **B.** The code causes an error because `words` is an array and `toUpperCase()` isn't a
  valid array function.
- [ ] **C.** The code causes an error because it will output `['JS', 'HTML', 'CSS']` three times.
- [ ] **D.** There is no error; the code generates the expected output.

### A.10. Identify the error

Which statement best describes the error below?

```js
const nums = [500, 200, 440];
const numStrings = [];
for (let i = 0; i <= nums.length; i++) {
  numStrings.push(nums[i].toString());
}
console.log(numStrings);
// expected output:
// ['500', '200', '440']
```

- [ ] **A.** The code causes an error because `numStrings` needs to be a `let` variable.
- [x] **B.** The code causes an error because `i <= nums.length` should be `i < nums.length`
- [ ] **C.** The code causes an error because `i++` isn't valid JavaScript syntax.
- [ ] **D.** There is no error; the code generates the expected output.

### A.11. Identify the error

Which statement best describes the error below?

```js
function outputArgs(a, b, c) {
  if (a) {
    console.log(a);
  }
  if (b) {
    console.log(b);
  }
  if (c) {
    console.log(c);
  }
}
outputArgs('hi', 'bye');
// expected output:
// hi
// bye
```

- [ ] **A.** The code causes an error because `outputArgs` takes in three arguments but it's being
  called with just two.
- [ ] **B.** The code causes an error because it will output `hi`, `bye`, and `undefined` instead
  of the expected output.
- [ ] **C.** The code causes an error because the `a`, `b`, and `c` variables haven't been
  initialized.
- [x] **D.** There is no error; the code generates the expected output.

## B. Free response

### B.1. Answer the questions below in your own words.

**_What is the purpose of functions?_**

```
Functions can be used to create named blocks of code that can be executed/reused later. They help you keep code DRY and maintainable.
There are tasks you will find yourself doing over and over. Instead of using subrutines, we can now package things beautifully as an invocable function. YAY
```

**_What is the difference between `console.log` and `return`?_**

```
console.log() outputs text to a display. return passes a value as the result of an invoked function.
```

**_What's the difference between defining and calling a function?_**

```
Calling a function does whatever the function is designed to do (endless possibilities). In order to call a function it must be defined somewhere. Defining it specifies the behavior that will execute when you invoke the function. However you can define a function and nothing will ever happen until/if it is invoked somewhere.
```

### B.2. Describe these data types.

Write a short description of the following data types:

**_String_**

```
A string is a sequence of characters. It is immutable, iterable, and has a bunch of cool attributes and methods like .toUpperCase() and .length. Seems like the default data type for input, output, and storage/transfer.
Denoted by double quotes, single quotes, or back tics.
```

**_Number_**

```
As far as I can tell this is a generic term for numerical data types. I think it includes ints, floats and bigInts to name a few. You can do what you would expect with numbers. Most numerial operations are supported natively in js. Very useful data type.
Denoted in many ways but the most simple is just typing a number in: 2.71828 or 42 etc.
```

**_Boolean_**

```
Booleans are logical data types true and false. They are used for control logic to get your program to operate correctly. There are some tricky "falsy" and "truthy" situations where other data types evaluate to true or false but mostly they come from evaluating comparison operators.
Boolean literals are typed out: true and false
```

**_Array_**

```
Arrays are simply an indexed list of other objects. Each object in the list has an index to identify it starting at 0 and going to array.length - 1. Arrays can be nested.
Denoted with []
```

### B.3. Trace the value of `x`

Consider the following program:

```js
let x = 5;
let y = 0;
while (y < 3) {
  x = x + 5;
  y = y + 1;
  console.log(x);
}
```

The lines below represent the value of `y` and `x` at the end of each iteration of the `while` loop.
Given the values for `y`, replace the `??` with the values for `x`. The first line has been
completed for you.

```
Initial values: y = 0, x = 5
1:              y = 1, x = 10
2:              y = 2, x = 15
3:              y = 3, x = 20
```
