# Kata 3: Reverse a String

## Goal

Write a function that reverses a string using fluent method chaining.

## Examples

```js
reverseString("hello"); // "olleh"
reverseString("abc"); // "cba"
reverseString("race car"); // "rac ecar"
reverseString(""); // ""
```

## Requirements

- Create a function named `reverseString`.
- Accept one argument: a string.
- Use `.split("")`, `.reverse()`, and `.join("")`.
- Return the reversed string.

## Starter Code

```js
function reverseString(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(reverseString("hello") === "olleh");
console.log(reverseString("abc") === "cba");
console.log(reverseString("race car") === "rac ecar");
console.log(reverseString("") === "");
```

## Hints

- Strings do not have a `.reverse()` method.
- Arrays do have a `.reverse()` method.
- Convert the string to an array, reverse it, then convert it back to a string.

## Stretch Goals

- Reverse the string after removing spaces.
- Reverse the string after removing non-ASCII characters.

Hint: this regular expression matches non-ASCII characters:

```js
/[^\x00-\x7F]/g
```

