# Spirkin Ilya
## Frontend developer
___

## Contact Information

__Phone:__ +375 29 798-52-22

__E-mail:__ spirkinilya@gmail.com

__Telegram:__ @chem_st

__Location:__ Minsk, Belarus

___

## About me

Junior Web Developer specializing in front end development. From 2022 start to learn HTML/CSS. Made several simple projects, including internet shop, using MODX Revo as CMS. Want to improve my professional skills in web development, will be glad to work in command.

___

## Skills

- HTML/CSS
- JavaScript (Basic)
- Git, Git Bash
- BEM
- MODX Revolution

## Code Example

__Task__

Given an array of integers.

Return an array, where the first element is the count of positives numbers and the second element is sum of negative numbers. 0 is neither positive nor negative.

If the input is an empty array or is null, return an empty array.

__Solution__
```javascript
function countPositivesSumNegatives(input) {
  if (!input || input.length === 0)
    return [];
  let positiveCounter = 0;
  let negativeSum = 0;
  let output =[];
  
  for (let i = 0; i < input.length; i++) {
    input[i] <= 0 ? negativeSum += input[i] : positiveCounter++
  }
  return [positiveCounter, negativeSum];
}
```
___

## Courses:

- 2023 RS Schools Course «JavaScript/Front-end.» (in progress)

## Languages:

- Russian
- Belarusian
- English (B1)