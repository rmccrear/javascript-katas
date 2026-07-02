# Kata 3: Count Letter A

## Goal

Write a function that counts how many times the letter `"a"` appears in a string.

## Examples

```js
countLetterA("banana"); // 3
countLetterA("apple"); // 1
countLetterA("bbb"); // 0
countLetterA(""); // 0
```

## Requirements

- Create a function named `countLetterA`.
- Accept one argument: a string.
- Count lowercase `"a"` characters.
- Return the final count as a number.

## Starter Code

```js
function countLetterA(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(countLetterA("banana") === 3);
console.log(countLetterA("apple") === 1);
console.log(countLetterA("bbb") === 0);
console.log(countLetterA("") === 0);
```

## Hints

- Start a counter at `0`.
- Loop through the string from front to back.
- Each time the current character is `"a"`, add `1` to the counter.

## Stretch Goals

- Count uppercase `"A"` as well.
- Let the caller choose which letter to count.

