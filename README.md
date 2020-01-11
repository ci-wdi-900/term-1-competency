# Term 1 Competency

### Steps To Get Started

1. Install `node` and `npm` if they're not already present.
2. `cd` into this directory in your terminal.
3. Run `npm install` and `npm test` in a terminal you can devote to monitoring your progress in the assignment--preferably a terminal you can full-screen.
4. Code the functions in `main.js` according to the specifications given below and outlined in detail in the tests. Check your terminal for feedback on which aspect of the problem you have yet to complete, and read `main.test.js` for the specifications' implementation; it makes explicit exactly what outputs are expected given the test inputs.


### Exam Question Descriptions

1. `fizzBuzzSingleNumber` - For most numbers given, this function returns the number unchanged. For a number divisible by 3, it _instead_ returns the string `'Fizz'`. For a number divisible by 5, it returns the string `'Buzz'`. For a number divisible by _both 3 and 5_, it returns the string `'FizzBuzz'`.
2. `rotateLetters` - This function returns an encoded string from the string given to it, "rotating" the letters along the alphabet according to the given offset. So with an offset of `1` and a string of `'adam'`, we get the string `'bebn'` back, because `'b'` is the next letter after `'a'`, `'e'` one letter after `'d'`, and so on. With a higher offset, you move the letter further to the right. With a negative number, you get a letter to the left instead. And if an offset brings the letter past `'z'` in one direction or `'a'` in the other, it wraps back around; `'z'` offset by `2` becomes `'b'`, and `'a'` offset by `-5` becomes `'v'`.
3. `uppercaseCount` - Takes in an array of words and returns a number: the count of words in that array that are entirely uppercased. `'HELLO'` would add to the count, while `'hello'` would not, and nor would `'heLLo'`.
4. `addToMultiDigitNumbers` - Takes in an array of numbers in string format and returns an array of numbers in string format, but with the given number added to each multi-digit one. So given a `3`, a `'50'` would become `'53'` and a `'19'` would become `'22'`, but a `'5'` would stay a `'5'`, since it's a single digit number. Keep in mind that the numbers in the array are in string format, and need to be outputted in string format as well.
5. `singlesOnly` - Given an array of objects representing people, returns an array of those people whose `status` property is NOT equal to `'married'`.
6. `getMeanAverageSalaryOfWomen` - Given an array of objects representing people, returns the mean average (what lay people just call "average") of the values of their `salary` properties, but only counting those people whose `gender` property is set to `'female'`.