# Kata 4: Count Letter A

## Goal

Write a function that counts how many times the letter `"a"` appears in a string using array methods.

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
- Use `.split("")`, `.filter()`, and `.length`.
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

- Split the string into characters.
- Filter the characters that equal `"a"`.
- Use `.length` on the filtered array.

## Stretch Goals

- Count uppercase `"A"` as well.
- Let the caller choose which letter to count.

