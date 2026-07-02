# Kata 6: Clean and Reverse a Phrase

## Goal

Write a function that cleans a phrase, then reverses it.

The cleaned phrase should be lowercase and should not contain spaces.

## Examples

```js
cleanAndReversePhrase("Hello World"); // "dlrowolleh"
cleanAndReversePhrase(" Race Car "); // "racecar"
cleanAndReversePhrase("A B C"); // "cba"
cleanAndReversePhrase(""); // ""
```

## Requirements

- Create a function named `cleanAndReversePhrase`.
- Accept one argument: a string.
- Convert the string to lowercase.
- Remove spaces.
- Reverse the remaining characters.
- Return the final string.

## Starter Code

```js
function cleanAndReversePhrase(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(cleanAndReversePhrase("Hello World") === "dlrowolleh");
console.log(cleanAndReversePhrase(" Race Car ") === "racecar");
console.log(cleanAndReversePhrase("A B C") === "cba");
console.log(cleanAndReversePhrase("") === "");
```

## Hints

- Chain the work in small steps.
- Use `.toLowerCase()` before comparing or reversing.
- You can use `.split(" ").join("")` to remove spaces.
- You can use `.split("").reverse().join("")` to reverse a string.

## Stretch Goal

Remove all non-alphanumeric characters before reversing.

Hint: this regular expression matches any character that is not a letter or number:

```js
/[^a-z0-9]/g
```

