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

<details>
<summary>Click for hints</summary>

If this is tough, try working through earlier katas in the series:

- [Kata 1: Print Forward Without Spaces](./kata-01-print-forward-no-spaces.md) - practice scanning a string from front to back with a counter.
- [Kata 2: Print Backward](./kata-02-print-backward.md) - reinforces that a counter can move through a string in either direction.

- Start a counter at `0`.
- Loop through the string from front to back.
- Each time the current character is `"a"`, add `1` to the counter.

</details>

## Stretch Goals

- Count uppercase `"A"` as well.
- Let the caller choose which letter to count.
