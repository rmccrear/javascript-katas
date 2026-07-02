# Kata 1: Print Forward Without Spaces

## Goal

Write a function that reads a string from front to back and prints the characters while skipping spaces.

For testing, return the final string after you build it.

## Examples

```js
printForwardNoSpaces("hello world"); // "helloworld"
printForwardNoSpaces("a b c"); // "abc"
printForwardNoSpaces(" no spaces "); // "nospaces"
printForwardNoSpaces(""); // ""
```

## Requirements

- Create a function named `printForwardNoSpaces`.
- Accept one argument: a string.
- Loop through the string from the first character to the last character.
- Skip space characters.
- Return the new string.

## Starter Code

```js
function printForwardNoSpaces(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(printForwardNoSpaces("hello world") === "helloworld");
console.log(printForwardNoSpaces("a b c") === "abc");
console.log(printForwardNoSpaces(" no spaces ") === "nospaces");
console.log(printForwardNoSpaces("") === "");
```

## Hints

- Use a counter that starts at `0`.
- Move the counter forward one step at a time.
- Build a result string as you go.
- Only add the current character when it is not a space.

## Stretch Goal

Filter out non-ASCII characters too.

Hint: this regular expression matches non-ASCII characters:

```js
/[^\x00-\x7F]/
```

