# Welcome to the MFPL official website!

## Note: This website only explains the basics of MFPL. how to build can be found in the readme file of the MFPL-python repository...

### Prerequisite: [MFPL-python](https://github.com/jason-kills-u/MFPL-python)

## Tutorial

MFPL is similar to brainf*ck. The only difference is that instead of symbols, MFPL uses words, like '+': plus. Please note that loops aren't added since this is still beta.

1. Create a file with the name "test.mfpl" with the content "add add out done".
3. run ./mfpl test.mfpl or mfpl test.mfpl
4. The output should be 'C'
5. Why? MFPL uses the cell system like brainf*ck but every cell has a default value of 64, which in ascii is 'A'. When there is a word "add", the value in the cell you are in is added by one, making it 'B'. And so on... The output of ./mfpl test.mfpl is 'C' because the value in the first cell is added by two(there are two adds in test.mfpl) making it 66 which is the ascii value of 'C'. Then there is an out word which outputs the ascii character form of the ascii value in the current cell. Which in turn, outputs 'C'. And at the end, done which signals the end of program.

There are more words you can explore outside of this tutorial, like sub, movr, movl.
