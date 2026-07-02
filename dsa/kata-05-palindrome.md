# Kata 5: Palindrome Checker

## Goal

Write a function that determines whether a string is a palindrome.

A palindrome reads the same forward and backward after ignoring capitalization, spaces, punctuation, and symbols.

## Examples

```js
isPalindrome("racecar"); // true
isPalindrome("RaceCar"); // true
isPalindrome("A man, a plan, a canal: Panama"); // true
isPalindrome("hello"); // false
isPalindrome("Was it a car or a cat I saw?"); // true
isPalindrome(""); // true
```

## Requirements

- Create a function named `isPalindrome`.
- Accept one argument: a string.
- Return `true` if the string is a palindrome.
- Return `false` if the string is not a palindrome.
- Ignore case.
- Ignore non-alphanumeric characters.

## Starter Code

```js
function isPalindrome(text) {
  // Your code here
}
```

## Test Cases

```js
console.log(isPalindrome("racecar") === true);
console.log(isPalindrome("RaceCar") === true);
console.log(isPalindrome("A man, a plan, a canal: Panama") === true);
console.log(isPalindrome("hello") === false);
console.log(isPalindrome("Was it a car or a cat I saw?") === true);
console.log(isPalindrome("") === true);
console.log(isPalindrome("0P") === false);
```

## Hints

- Normalize the string before comparing characters.
- `toLowerCase()` can help with capitalization.
- A regular expression can remove punctuation and spaces.
- Use the counter pattern twice: one counter moves from front to back, and one counter moves from back to front.
- A two-pointer loop can compare the left and right sides without reversing the string.

## Stretch Goals

- Solve it once by cleaning the string and reversing it.
- Solve it again using two pointers.
- Explain the time and space complexity of both approaches.
- Add support for inputs that are not strings by returning `false`.

## Reflection

After solving, answer these questions:

1. What edge cases did you test?
2. Which solution is easier to read?
3. Which solution uses less extra memory?
