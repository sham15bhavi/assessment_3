

TO CHECK WHETHER NUMBER IS EVEN OR ODD
This Solidity contract is called EvenOrOdd, and it has a function checkEvenOrOdd that takes a uint256 input and returns whether the number is "Even" or "Odd".

Requirements
Solidity version 0.8.0 or higher

Usage
Interact with the contract using the following functions:
(1) The require statement checks if the input number is greater than 0. If it's not, the function will revert with the error message "Number must be positive".
(2) The assert statement checks if the input number is less than or equal to type(uint256).max / 2 + 1. This check ensures that the number is not too large, preventing potential overflows.
(3)  If this condition is not met, the function will also revert without a custom error message.

Output
If the input number is even, the function returns the string "Even".
If the input number is odd, the function returns the string "Odd".

LICENSE
// SPDX-License-Identifier: MIT

https://www.loom.com/share/58ab6921c19d4fd49bb08bd27d73368b?sid=c9d4f1ef-1e49-4d89-a7ee-6a118dee27f1
