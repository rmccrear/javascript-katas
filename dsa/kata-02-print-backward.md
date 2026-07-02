# Kata 2: Print Backward

## Goal

Write a function that reads a string from back to front and prints the characters in reverse order.

For testing, return the final string after you build it.

## Examples

```js
printBackward("hello"); // "olleh"
printBackward("abc"); // "cba"
printBackward("race car"); // "rac ecar"
printBackward(""); // ""
```

## Requirements

- Create a function named `printBackward`.
- Accept one argument: a string.
- Loop through the string from the last character to the first character.
- Return the reversed string.

## Starter Code

```js
function printBackward(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(printBackward("hello") === "olleh");
console.log(printBackward("abc") === "cba");
console.log(printBackward("race car") === "rac ecar");
console.log(printBackward("") === "");
```

## Hints

- Use a counter that starts at `text.length - 1`.
- Move the counter backward one step at a time.
- Build a result string as you go.

## Stretch Goal

Filter out spaces and non-ASCII characters while printing backward.

Hint: this regular expression matches non-ASCII characters:

```js
/[^\x00-\x7F]/
```

