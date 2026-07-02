# Kata 2: Remove Spaces

## Goal

Write a function that removes all space characters from a string using fluent method chaining.

## Examples

```js
removeSpaces("a b c d"); // "abcd"
removeSpaces("hello world"); // "helloworld"
removeSpaces(" no spaces "); // "nospaces"
removeSpaces(""); // ""
```

## Requirements

- Create a function named `removeSpaces`.
- Accept one argument: a string.
- Use `.split()` and `.join()`.
- Return the string without spaces.

## Starter Code

```js
function removeSpaces(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(removeSpaces("a b c d") === "abcd");
console.log(removeSpaces("hello world") === "helloworld");
console.log(removeSpaces(" no spaces ") === "nospaces");
console.log(removeSpaces("") === "");
```

## Hints

- Split the string on `" "`.
- Join the pieces back together with `""`.
- This is the fluent version of manually building a string while skipping spaces.

## Stretch Goals

- Remove tabs and newlines too.
- Remove all non-ASCII characters.

Hint: this regular expression matches non-ASCII characters:

```js
/[^\x00-\x7F]/g
```

