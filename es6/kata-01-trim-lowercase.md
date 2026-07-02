# Kata 1: Trim and Lowercase

## Goal

Write a function that removes extra space from the beginning and end of a string, then converts it to lowercase.

## Examples

```js
normalizeText("  Hello WORLD  "); // "hello world"
normalizeText(" JAVASCRIPT "); // "javascript"
normalizeText("already clean"); // "already clean"
normalizeText(""); // ""
```

## Requirements

- Create a function named `normalizeText`.
- Accept one argument: a string.
- Use method chaining.
- Return the cleaned string.

## Starter Code

```js
function normalizeText(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(normalizeText("  Hello WORLD  ") === "hello world");
console.log(normalizeText(" JAVASCRIPT ") === "javascript");
console.log(normalizeText("already clean") === "already clean");
console.log(normalizeText("") === "");
```

## Hints

- Start with the original string.
- Chain `.trim()` and `.toLowerCase()`.
- The order matters if you want the result to read like a cleanup pipeline.

## Stretch Goals

- Also remove extra spaces between words.
- Return `""` when the input is not a string.

