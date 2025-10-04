•	Why you chose each loop type for each challenge
I chose to use a while loop for Challenge One because there is no set amount of times the loop will be iterated until the user inputs a number.
I used a for loop for Challenge Two because it needed to iterate over a container (specifically a range, which is most often used in for loops).


•	How your solutions work
The first solution, Challenge One, works by first checking if the current number is above one (since we need to make the Collatz Conjecture sequence), and then checking if that number is divisible by two - if it is, we take that number and divide it by two, and add a step to the counter (which measures how many iterations the loop takes to get to the final number). Else, the number is NOT divisible by two, and we take that number and multiply it by three, and then add one (as well as adding one to the step counter). This continues until the number is less than one. It then prints "1" to finish the sequence. It also prints the final step count.

The second solution, Challenge Two, the program takes another input from the user and first checks if that number is equal to two (as two is a special case in this situation); if it is, the program prints out that it is a prime number. Otherwise, the program checks a range made from 2 to the user-number minus one (2, second_number - 1), and checks if any number in that list will be the result of the user's number % 3; if it is, the program prints out "{second_number} is prime!". If the user's number % 3 is NOT equal to any number in the range, then it prints out "{second_number} is not prime (divisible by 3)". There are breaks after each print statement to make sure it does not keep printing.

The third solution, Challenge Three, makes a range for the number of rows and columns. Then, the program prints the header of the multiplication table (in a seperate section since it's formatted differently). It then prints out the full table, with the numbers evaluated by multiplying the number in the column by the number in the row; all of the numbers are spaced evenly from one another in order to maximize organization.


•	Any AI assistance used
I used ChatGPT to help me properly format the table header as well as printing out the table (I was originally doing the multiplication in the wrong way).

Final Git: git add README.md + git commit -m "Add loop design documentation"
