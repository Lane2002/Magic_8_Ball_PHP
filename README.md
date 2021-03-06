# Magic_8_Ball_PHP
LEARN PHP
Magic 8 Ball
The Magic 8-Ball is a popular toy used for fortune-telling or seeking advice.

In this project, you’ll be creating a function that can answer any “yes” or “no” question.

Magic 8-Ball, should I do this project?

The answers inside a standard Magic 8-Ball are:

It is certain.
It is decidedly so.
Without a doubt.
Yes - definitely.
You may rely on it.
As I see it, yes.
Most likely.
Outlook good.
Yes.
Signs point to yes.
Reply hazy, try again.
Ask again later.
Better not tell you now.
Cannot predict now.
Concentrate and ask again.
Don't count on it.
My reply is no.
My sources say no.
Outlook not so good.
Very doubtful.
Your magic8Ball() will take in any “yes” or “no” question (as a string) and give a psychic (random) answer.

Tasks
10/10 Complete
Mark the tasks as complete by checking them off
Creating the Function "Skeleton"
1.
Define a magic8Ball() function.


Stuck? Get a hint
2.
Your magic8Ball() function should prompt the player to enter a yes or no question they want to have answered. Feel free to add some personal flare to this. Use the readline() function to take in their question. Save this as a variable.


Stuck? Get a hint
3.
Use echo to print a message to the terminal. The message should state the received question. Print the question you received. You should feel free to add more dramatic flourishes.


Stuck? Get a hint
Generating the random number
4.
Your “magic” answer will be determined by a random integer. We have 20 possible responses. Generate a random integer between 0 and 19 (inclusive) and save it to a variable.


Stuck? Get a hint
5.
Add a line to your program which uses echo to print the random number. We’ll comment out this part of the code later, but it will be useful for testing our code so far.


Stuck? Get a hint
Test your function
6.
Let’s test your project so far. After your function definition, invoke your function a few times.


Stuck? Get a hint
7.
Run your program—providing different questions each time you’re prompted. Make sure that your message with the question and the random number are displaying as expected.


Stuck? Get a hint
Add the conditional logic
8.
Now it’s time to add the decision-making power to your program. You can accomplish this with either a series of if/elseif statements or a switch statement.

Your function should print the response associtated with the random number you generated:

If the number is 0, It is certain. should be printed
If the number is 1, It is decidedly so. should be printed
If the number is 2, Without a doubt. should be printed
If the number is 3, Yes - definitely. should be printed
If the number is 4, You may rely on it. should be printed
If the number is 5, As I see it, yes. should be printed
If the number is 6, Most likely. should be printed
… and so on.

Check out the hint if you’d like some help getting started.


Stuck? Get a hint
9.
If you haven’t already, comment out or remove the line of code where you echo the random number, and run your code again. You should see all of your questions answered!

Extra Challenges
10.
Now that you’ve completed the project consider these extra challenges:

Refactor your code: try to make your code as concise and easy to read as possible.
If you used if/elseif statements, try to rewrite the code using a switch statement or vice versa.
Customize the program to your taste—get creative!
