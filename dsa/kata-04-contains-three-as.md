# Kata 4: Contains At Least Three A's

## Goal

Write a function that returns `true` when a string contains at least three lowercase `"a"` characters.

## Examples

```js
containsAtLeastThreeAs("banana"); // true
containsAtLeastThreeAs("apple"); // false
containsAtLeastThreeAs("abracadabra"); // true
containsAtLeastThreeAs("bbb"); // false
```

## Requirements

- Create a function named `containsAtLeastThreeAs`.
- Accept one argument: a string.
- Count lowercase `"a"` characters.
- Return `true` if the count is at least `3`.
- Return `false` if the count is less than `3`.

## Starter Code

```js
function containsAtLeastThreeAs(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(containsAtLeastThreeAs("banana") === true);
console.log(containsAtLeastThreeAs("apple") === false);
console.log(containsAtLeastThreeAs("abracadabra") === true);
console.log(containsAtLeastThreeAs("bbb") === false);
console.log(containsAtLeastThreeAs("") === false);
```

## Hints

- This starts the same way as `countLetterA`.
- Keep a counter as you scan the string.
- After the loop, compare the counter to `3`.

## Stretch Goals

- Return early as soon as the count reaches `3`.
- Count uppercase `"A"` as well.
- Let the caller choose the letter and the minimum count.

