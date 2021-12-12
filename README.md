# Brainfuck TI-Basic Interpreter
A Brainfuck interpreter made with TI-Basic for Texas Instruments' calculators. Available for TI 83/84/+/SE.

TI-Basic isn't very fast nor is my code, but hey, this is Brainfuck, who cares?

## Usage
Load BF.8xp on your calculator using TI Connect and run it. You'll be asked to input the Brainfuck code.
The only difference between normal Brainfuck code and the one you're supposed to input is that you should use curly brackets instead of square ones.
**Use `{}` instead of `[]`**.

Also, the code **can't** have any characters other than the usual (`.,+-<>{}`), so strip it of comments and spaces.

Lastly, the code is stored in the `Str1` variable and if you input `0` instead of your code, the code stored in `Str1` will be run.
This way, you can re-run the last code you executed or edit the `Str1` var and then run it.
