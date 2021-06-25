# Project-Decoder-Ring
thinkful project 

Project: Decoder Ring
You are planning a surprise birthday party for one of your friends who loves escape rooms and puzzles. What better way to practice your new coding skills then to build an application that will help you encode and decode all kinds of fun messages?

![Alt text](https://res.cloudinary.com/strive/image/upload/w_1000,h_1000,c_limit/7a945612b738d811880b0244ee5ec0a2-image.png?raw=true "Optional Title")


This project is designed to test your ability to build tricky algorithms as well as write unit tests with Mocha & Chai. Before taking on this module, you should be comfortable with the following:

Installing packages via NPM.
Modifying the package.json file with new scripts.
Running tests from the command line.
Writing JavaScript functions.
Writing tests for specific functions.
Iterating through strings, objects, and arrays.
Debugging through reading errors and using the VSCode debugger.



The Caesar Shift is a type of substitution cipher originally used by Julius Caesar to protect messages of military significance. It relies on taking the alphabet and "shifting" letters to the right or left, based on the typical alphabetic order.

For example, if you were to "shift" the alphabet to the right by 3, the letter "A" would become "D".

![Alt text](https://res.cloudinary.com/strive/image/upload/w_1000,h_1000,c_limit/b6a94b251bbbe6dae7e3e84ed8be33a4-image.png?raw=true "Optional Title")





![Alt text]( https://img.wattpad.com/de1734902dd68a5b526b62eaecc6d6ddf3689f4d/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f776174747061642d6d656469612d736572766963652f53746f7279496d6167652f566c6c694271675147655f6845773d3d2d36352e313463656639363034303930633264383539383839383035393533392e6a7067?s=fit&w=720&h=720 "Optional title")

  
 
  
The Polybius Square is a cipher that is achieved by arranging a typical alphabet into a grid. Each letter is represented through a coordinate. For example, in the above table, the letter "B" would be represented by the numerical pair "21".

Typically, it is possible to arrange the letters however you like and read off the coordinates in whatever direction you like. In this example, the grid will be arranged as above and coordinates will be read by comparing the first digit to the number on the top of the table and the second digit to that on the left.

"thinkful" -> "4432423352125413"
When decoding the message, each pair of numbers is translated using the coordinates.



![Alt text](https://res.cloudinary.com/strive/image/upload/w_1000,h_1000,c_limit/19c12a6ee38ceddd82d75e12edf53189-image.png "Optional title")

The Substitution Cipher requires a standard alphabet and a substitution alphabet. Letters from the standard alphabet will be transposed to the standard alphabet. This cipher requires that the recipient have the substitution alphabet, otherwise it will be difficult for them to decode the message.

For example, in the image above, the word "HELLO" would be translated as follows:

"H" becomes "R".
"E" becomes "M".
"L" becomes "W".
"O" becomes "L".
This would result in the code "RMWWL". To decrypt this code, you would simply take the result and transpose back from the substitution alphabet to the standard alphabet.







