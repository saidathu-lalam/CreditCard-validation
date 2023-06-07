# CreditCard-validation
A credit card number must have between 13 and 16 digits, and this can be checked by using Luhn algorithm.
Steps involved in the Luhn algorithm
Step 1 – Starting from the rightmost digit, double the value of every second digit, <br>
Step 2 – If doubling of a number results in a two digit number then add the digits of the product
         to get a single digit number. <br>
Step 3 – Now take the sum of all the digits.<br>
Step 4 – If the total modulo 10 is equal to 0 (if the total ends in zero) 
         then the number is valid according to the Luhn formula; else it is not valid.<br>


