# Kata 7: Palindrome Chain

## Goal

Write a palindrome checker using fluent string and array method chaining.

A palindrome reads the same forward and backward after ignoring capitalization, spaces, punctuation, and symbols.

## Examples

```js
isPalindromeChain("racecar"); // true
isPalindromeChain("RaceCar"); // true
isPalindromeChain("A man, a plan, a canal: Panama"); // true
isPalindromeChain("hello"); // false
isPalindromeChain("Was it a car or a cat I saw?"); // true
isPalindromeChain(""); // true
```

## Requirements

- Create a function named `isPalindromeChain`.
- Accept one argument: a string.
- Normalize the string with method chaining.
- Ignore case.
- Ignore non-alphanumeric characters.
- Return `true` if the normalized string matches its reversed version.
- Return `false` if it does not.

## Starter Code

```js
function isPalindromeChain(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(isPalindromeChain("racecar") === true);
console.log(isPalindromeChain("RaceCar") === true);
console.log(isPalindromeChain("A man, a plan, a canal: Panama") === true);
console.log(isPalindromeChain("hello") === false);
console.log(isPalindromeChain("Was it a car or a cat I saw?") === true);
console.log(isPalindromeChain("") === true);
console.log(isPalindromeChain("0P") === false);
```

## Hints

- First build a cleaned version of the input.
- Use `.toLowerCase()` to ignore capitalization.
- Use `.replace()` with a regular expression to remove non-alphanumeric characters.
- Use `.split("").reverse().join("")` to create the reversed version.

This regular expression matches any character that is not a lowercase letter or number:

```js
/[^a-z0-9]/g
```

## Stretch Goals

- Return `false` when the input is not a string.
- Solve the same problem without `.reverse()`.
- Explain the tradeoff between this chained version and the two-counter DSA version.

