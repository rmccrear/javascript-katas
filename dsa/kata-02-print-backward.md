# Kata 2: Print Backward

## Goal

Write a function that reads a string from back to front and prints the characters in reverse order.

Print each character on its own line with `console.log`.

## Examples

```js
printBackward("abc");
```

Output:

```text
c
b
a
```

## Requirements

- Create a function named `printBackward`.
- Accept one argument: a string.
- Loop through the string from the last character to the first character.
- Use `console.log` to print each character.
- Each printed character should appear on its own line.

## Starter Code

```js
function printBackward(text) {
  // Your code here
}
```

## Manual Tests

```js
printBackward("hello");
// o
// l
// l
// e
// h

printBackward("abc");
// c
// b
// a

printBackward("");
// prints nothing
```

## Hints

- Use a counter that starts at `text.length - 1`.
- Move the counter backward one step at a time.
- Look at one character per loop.
- Call `console.log` for the current character.

## Stretch Goal

Filter out spaces and non-ASCII characters while printing backward.

Hint: this regular expression matches non-ASCII characters:

```js
/[^\x00-\x7F]/
```
