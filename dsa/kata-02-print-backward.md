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

<details>
<summary>Click for hints</summary>

If this is tough, try working through earlier katas in the series:

- [Kata 1: Print Forward Without Spaces](./kata-01-print-forward-no-spaces.md) - practice moving a counter through a string and printing one character at a time.

- Use a counter that starts at `text.length - 1`.
- Move the counter backward one step at a time.
- Look at one character per loop.
- Call `console.log` for the current character.

</details>

## Stretch Goal

Filter out spaces and non-ASCII characters while printing backward.

<details>
<summary>Click for stretch hint</summary>

This regular expression matches non-ASCII characters:

```js
/[^\x00-\x7F]/
```

</details>
