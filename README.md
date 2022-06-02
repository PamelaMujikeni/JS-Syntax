# Learning JS-Syntax through these 3 simple exercises. 

TASK 1
Deep in his mountain-side meteorology lab, the mad scientist Kelvin has mastered weather prediction.Recently, 
Kelvin began publishing his weather forecasts on his website. However,there’s a problem: All of his forecasts 
describe the temperature in Kelvin. With your knowledge of JavaScript, you need to convert Kelvin to Celsius, 
then to Fahrenheit.
Follow the instructions below:

1. Create a new file called kelvin_weather.js
2. The forecast today is 293 Kelvin. To start, create a variable named kelvin, and set it equal to 293.
The value saved to kelvin will stay constant. Choose the variable type with this in mind. 

3.Write a comment above that explains this line of code.

4.Celsius is similar to Kelvin —the only difference is that Celsius is 273degrees less than Kelvin.Let’s convert Kelvin 
to Celsius by subtracting 273 from the kelvin variable. Store the result in another variable, namedcelsius.

5.Write a comment above that explains this line of code.

6.Use this equation to calculate Fahrenheit, then store the answer in a variable
namedfahrenheit.Fahrenheit = Celsius * (9/5) + 32 In the next step we will round the number saved tofahrenheit. 
Choose the variable type that allows you to change its value.

7.Write a comment above that explains this line of code.

8.When you convert from Celsius to Fahrenheit,you often get a decimal number.Use the.floor()method from the built-in 
Math object to round down the Fahrenheit temperature. Save the result to thefahrenheitvariable.

9.Write a comment above that explains this line of code.


10.Useconsole.logand string interpolation to log the temperature infahrenheitto the console as follows: 
The temperature is TEMPERATURE degreesFahrenheit.Use string interpolation to replaceTEMPERATUREwith the 
value saved tofahrenheit.

11.By using variables, your program should work for any Kelvin temperature —just change the value of kelvin and 
run the program again. 

What’s 0 Kelvin in Fahrenheit?










TASK 2
Built a Magic Eight Ball(for telling fortunes) with the following instructions:

1.In the first line of the program, define a variable called userName that is set to an empty string.If the user wants, they can enter their name in between the quotation marks.

2.Below this variable, create a ternary expression that decides what to do if the user enters a name or not. If the user enters a name —like'Jane'—use string interpolation to logHello, Jane!to the console. Otherwise, simply logHello!.

3.Create a variable nameduserQuestion. The value of the variable should be a string that is the question the user wants to ask the Magic Eight Ball.

4.Write aconsole.log()for theuserQuestion, stating what was asked. You can include the user’s name in theconsole.log()statement, if you wish!

5.We need to generate a random number between 0 and 7. Create another variable, and name itrandomNumber. Set it equal to this expression, which uses two methods (Math.floor()andMath.random()) from the Math library.

6.Create one more variable namedeightBall, and set it equal to an empty string. We will save a value to this variable in the next steps, depending on the value ofrandomNumber.

7.We need to create a control flow that takes in therandomNumberwe made in step 5, and then assignseightBallto a reply that a Magic Eight Ball would return. Think about utilizingif/elseorswitchstatements. Here are 8 Magic Eight Ball phrases that we’dlike to save to the variableeightBall:'It is certain''It is decidedly so''Reply hazy try again''Cannot predict now''Do not count on it''My sources say no''Outlook not so good''Signs point to yes'

8.If the randomNumber is 0, then save an answer to the eightBall variable; if randomNumber is 1, then save the next answer, and so on. If you’re feeling creative, make your own responses!

9.Write aconsole.log()to print the Magic Eight Ball’s answer, the value of theeightBallvariable.

10.Run your program a few times to see random results appear in the console!











TASK 3

Southampton’s annual race is just around the corner! This year we have a LOT of participants.
You have been hired to write a program that will register runners for the race and give them instructions on race day.

Here’s how the registration works:

•There are adults runners (18+) and youth runners (under 18s).
•They can register early or late.
•Runners are assigned a race number and start timebased on their age and registration.
•Race number:
      oEarly adults receive a race number at or above 1000
      oAll others receive a number below 1000
•Start time:
      oAdults run at 9:30am or 11:00am
          §Early adults run at 9:30am.
          §Late adults run at 11:00am.
      oYouth registrants run at 12:30pm.

Follow the below instructions:

1.Race numbers are assigned randomly. Here’s the first line of code to get you going J:let raceNumber= Math.floor(Math.random() * 1000);

2.Create a variable that indicates whether a runner registered early or not.Set it equal to a Boolean value. You can change this later to test different runners. 

3.Create a variable for the runner’s age and set it equal to a number.You’ll change this later as you test different runner conditions.

4.Create a control flow statement that checks whether the runner is an adult AND registered early.Add1000to theirraceNumberif this is true.

5.Create a separate control flow statement below the first (starting withifagain). This statement will check age and registration time to determine race time. For runners over 18 who registered early, log a statement to the console telling them that they will race at 9:30 am. Include theirraceNumber.

6.“Late adults run at 11:00 am”Since we already checked for early adults we can write a statement like this:else if runner is over 18 AND did not register early they will race at 11:00am. Write the correspondingelse ifstatement.Within that, log a string to the console telling them that they will race at 11:00 am. Include their raceNumber.

7.“Youth registrants run at 12:30 pm (regardless of registration)”. For people who are under 18, log a statement to the console telling them that they will race at 12:30 pm. IncludetheirraceNumber.

8.Enter different combinations of values for the two variables you created and run your code several times. Verify that the correct statements are printing to the console!

9.Don’t forget about runners exactly 18 years old!Add anelsestatement that logs a statement to the console telling the runner to see the registration desk.






