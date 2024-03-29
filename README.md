# How to Build and Run the Solution

I used NodeJS and Jest testing library to create my solution for this kata. If you are familiar with NodeJS and just need the command to run the solution, you can just type `npm test` into the command line. Otherwise, please follow my _Detailed Instruction_ below.

## Detailed Instruction

First of all, make sure that you have NodeJS installed on your machine. NodeJS allows you run JavaScript from the CMD/Terminal environment. You can get the instructions of downloading and installing NodeJS at https://nodejs.org/en/

Once you have NodeJS installed and ready on your machine, you can go ahead with the following steps:

1. Open up your terminal or CMD (you can `cd` to your own workspace directory if you prefer)
2. Within the cli, you can start typing `git clone https://github.com/vud531/kata-pencil-durability` to clone the solution repository
3. After that, you can type `cd kata-pencil-durability` to go to the solution directory
4. Finally, you can type `npm test` to start testing the modules/classes with jest

You should now be able to view the test results in the terminal.

# Notes

You may notice, I have created 2 `write()` methods, `write` and `writeFaster`.
The purpose of `writeFaster` is to optimize writing strings that are thousands of characters long, and have repeated patterns such as all whitespace char, or all lowercase char, or all uppercase char. The process of running and testing this `write` method can be demanding so I decided to create 2 different `write` methods, and commented out the test file of `writeFaster`. Feel free to uncomment it out and run it if you would like.
