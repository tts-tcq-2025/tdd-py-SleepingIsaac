#Feature
- Create StringCalculator that can take any amount of numbers and return their sum

# Requirement Specification
- Add method should be able to take an unknown amount of numbers
- Add method should work with any delimiter
- Numbers bigger than 1000 should be ignores
- If negative numbers are used, throw an exception saying "negative not allowed" - and the negative number used. If multiple negative numbers show them all in the exception
- Empty string call return 0

# Test Specification
- Add method should work with lines, comman, delimeters
- Delimiters can be of any length with the following format: “//[delimiter]\n” for example: “//[***]\n1***2***3” should return 6
- Ensure  maximum complexity (CCN) per function == 3
- Ensure 100% line and branch coverage at every step

