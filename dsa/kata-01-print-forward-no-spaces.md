# Kata 1: Print Forward Without Spaces

## Goal

Write a function that reads a string from front to back and prints the characters while skipping spaces.

Print each character on its own line with `console.log`.

## Examples

```js
printForwardNoSpaces("a b c");
```

Output:

```text
a
b
c
```

## Requirements

- Create a function named `printForwardNoSpaces`.
- Accept one argument: a string.
- Loop through the string from the first character to the last character.
- Skip space characters.
- Use `console.log` to print each non-space character.
- Each printed character should appear on its own line.

## Starter Code

```js
function printForwardNoSpaces(text) {
  // Your code here
}
```

## Manual Tests

```js
printForwardNoSpaces("hello world");
// h
// e
// l
// l
// o
// w
// o
// r
// l
// d

printForwardNoSpaces(" no spaces ");
// n
// o
// s
// p
// a
// c
// e
// s

printForwardNoSpaces("");
// prints nothing
```

## Hints

<details>
<summary>Click for hints</summary>

If this is tough, break this kata into smaller steps first:

- Print every character in the string with `console.log`.
- Add an `if` statement that checks whether the current character is a space.
- Only print when the current character is not a space.

- Use a counter that starts at `0`.
- Move the counter forward one step at a time.
- Look at one character per loop.
- Only call `console.log` when the current character is not a space.

</details>

## Stretch Goal

Filter out non-ASCII characters too.

<details>
<summary>Click for stretch hint</summary>

This regular expression matches non-ASCII characters:

```js
/[^\x00-\x7F]/
```

</details>
