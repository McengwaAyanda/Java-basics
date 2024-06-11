# Java-basics
fundamentals of java for beginners

Java program is an object-oriented programming language, that means java is the collection of objects, and these objects communicate thhrough method callss to each other to work together.
# Basic terminologies in java
Class: is a blueprint(plan) of the instance of a class(object). It can be defined as a logical template that share common properties and methods
Object: is an instance of a class. it is an entity that has behavior and state.
Method: The behavior of an object is the method.
Instance variables: Every object has its own unique set of instance variables. The state of an object is generally created by the values that are assigned to these instance variables.
# Java Basic Syntax

There are 3 types of comments in Java
1. //Single line comments
2. /*Multi-line comments*/
3. /** Doc comment or docummentation comment*/

The name of a source file should exactly match the public class name with the extension of .java
Java is a case-sensitive language, which means that the identifiers AB, Ab, aB and ab are different in java
The first letter of the class should be in Uppercase
If several words are used to form the name of the class, each inner words first letter should be in Uppercase. underscores are allowed but not recommended. Also allowed are numbers and currency symbols, although the latter are also discouraged because they are used for a special purpose(for inner and annonymous classes).
The method main() is the main entry point into a java program: this is where the processing starts. 
All the methods names should start with a lowercase letter.
If several words are used to form the name of the method, then each first letter of the inner word should be i uppercase.
Identifiers are the names of local variables, instance and class variables, and labels, but also the names for classes, packages, modules and methods. All unicode characters are valid, not just the ASCII subset.
All Identifiers can begin with a letter, a  currency symbol or an underscore. According to the convention, a letter should be lower case for variables. 
Identifiers are case-sensitive and keywords cannot be used as identifiers as they are reserved words and contain special meanings.

# Decision Structures in Java
# If statements
Like individuals, computers also have to make decisions from time to time. An "if statement" is a unique tool that a computer can utilize when it needs to make a choice.
The "if statement" functions as a route branching. The computer encounters this bifurcation while continuing on its typical course. The "if" path will be followed by the computer if a specific event occurs. Should it fail, the computer will continue on the default route.
 e.g. Let's take an example where a salesperson typically earns $1,000 every week. However, they receive a special $250 incentive if they sell more than ten items in a given week.
 ![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/622b46f9-ea42-4595-a572-317064953df1)


### If-else Statements
A decision structure called an if-else statement enables a computer to follow one of two routes based on whether a particular condition is satisfied. An if-else statement, for instance, could be used by a software to ascertain whether a salesman has reached their quota. A congrats message might print from the application once the salesperson has reached their quota. If not, the software can print a warning telling the salesman to give it more the next time.
This code determines if the user's quota was reached. They were told if they did. If not, they are informed of the number of sales they missed.
The quota is originally initialized to 10 by the code. Next, it inquires about the user's weekly sales total. It then determines whether the sales are higher.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/646ac969-7681-4408-bc56-aede3cbba6cc)


### If-else-if statements\
Imagine you're at school and you just took a test. The teacher is going to give you a grade, and there are 5 different grades you can get: A, B, C, D, or F.
The teacher is going to use a special tool called an "if-else-if statement" to figure out what grade to give you.
First, the teacher checks if your score is less than 60. If it is, they'll give you an F.
If your score is not less than 60, the teacher checks if it's less than 70. If it is, they'll give you a D.
If your score is not less than 70, the teacher checks if it's less than 80. If it is, they'll give you a C.
If your score is not less than 80, the teacher checks if it's less than 90. If it is, they'll give you a B.
If your score is not less than 90, the teacher will give you an A.
This "if-else-if" tool helps the teacher look at all the different possible scores and decide which grade is the right one for you. It's kind of like a big decision tree, with different branches for each possible grade.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/b6f0dc92-a531-488b-84ff-6d98640f204a)


### Switch statements
Imagine you're at school and the teacher asks you to tell them your grade. You look at your paper and see you got a letter grade, like an A, B, C, D, or F.
The teacher is going to use a special tool called a "switch statement" to figure out what message to give you based on your grade.
First, the teacher takes the grade you gave them and puts it in a special "grade" box.
Then, the teacher says, "Okay, let's see what message we should give based on the grade in this box."
The teacher starts going through a list of different "cases" - one for each possible grade (A, B, C, D, F).
For example, if the grade in the box is an 'A', the teacher says, "Aha, in the case of an 'A', we'll give the message 'Excellent job!'"
The teacher writes that message in another special "message" box.
If the grade is a 'B', 'C', 'D', or 'F', the teacher has different messages for each of those cases.
The cool thing is, the teacher only does the message for the one case that matches your grade. They don't have to check all the other cases.
But what if you put in something weird, like a 'Z'? The teacher has a special "default" case for that, where they can give a message like "I don't understand that grade."
So the "switch statement" is like a big decision tree that helps the teacher figure out the right message to give you based on your grade. It's a really helpful tool for the teacher!
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/97ac1a2e-5444-44c5-bc6d-277752d514e5)


### Switch Expressions
Imagine you're at school and the teacher asks you to tell them your grade. You look at your paper and see you got a letter grade, like an A, B, C, D, or F.
The teacher is going to use a special tool called a "switch expression" to figure out what message to give you based on your grade.
First, the teacher takes the grade you gave them and puts it in a special "grade" box.
Then, the teacher says, "Okay, let's see what message we should give based on the grade in this box."
The teacher starts going through a list of different "cases" - one for each possible grade (A, B, C, D, F).
For example, if the grade in the box is an 'A', the teacher says, "Aha, in the case of an 'A', we'll give the message 'Excellent job!'"
The cool thing is, the teacher doesn't have to write "message = 'Excellent job!'" - they can just put the message right there in the case.
If the grade is a 'B', 'C', 'D', or 'F', the teacher has different messages for each of those cases.
The best part is, the teacher doesn't have to write "break" at the end of each case. The switch expression knows to stop once it finds the right case.
Another neat thing is, if the teacher wants the same message for two different grades, they can just list the cases together, separated by a comma.
The teacher can also do more than just assign a message - they can run a whole little program inside each case if they need to.
So the "switch expression" is like a super-powered version of the regular "switch statement" that the teacher can use to make their job a lot easier. It's a really handy tool!
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/8c81cd83-cb4c-47cd-9367-42a76e46dc92)

### Relational Operators
Relational operators are like super-special tools that help us figure out if something is bigger, smaller, or the same as something else. They're kind of like the tools a builder uses to measure things.
There are 6 different relational operators, and each one has a special symbol:
1. Greater Than (>): This one checks if the number on the left is bigger than the number on the right. For example, if we ask "Is 5 greater than 3?" the answer is yes, because 5 is bigger than 3.
2. Less Than (<): This one checks if the number on the left is smaller than the number on the right. For example, if we ask "Is 2 less than 7?" the answer is yes, because 2 is smaller than 7.
3. Greater Than or Equal To (>=): This one checks if the number on the left is bigger than or the same as the number on the right. For example, if we ask "Is 4 greater than or equal to 4?" the answer is yes, because 4 is the same as 4.
4. Less Than or Equal To (<=): This one checks if the number on the left is smaller than or the same as the number on the right. For example, if we ask "Is 6 less than or equal to 10?" the answer is yes, because 6 is smaller than 10.
5. Equal To (==): This one checks if the two things are exactly the same. For example, if we ask "Is 3 equal to 3?" the answer is yes, because they are the same number.
6. Not Equal To (!=): This one checks if the two things are not the same. For example, if we ask "Is 5 not equal to 7?" the answer is yes, because 5 and 7 are different numbers.
These relational operators are super helpful when we need to make decisions, like if we should give someone a reward or not. They help us figure out if something is bigger, smaller, or the same as something else.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/f93fca54-b91d-4a6b-b47b-84ffea70c7ce)

### Logical Operators
These are the special tools that help us make complex decisions in Java.
Imagine you're a boss, and you need to decide if someone qualifies for a loan. To qualify, they need to meet two requirements:
1. Earn at least $30,000 per year
2. Have worked at their current job for at least 2 years
You can't just look at one condition - you need to check both. That's where logical operators come in!
There are three main logical operators in Java:
1. AND (&&): This operator checks if BOTH conditions are true. So, if the person earns $30,000 AND has worked for 2 years, they qualify.
2. OR (||): This operator checks if at least ONE of the conditions is true. So, if the person earns $30,000 OR has worked for 2 years, they qualify.
3. NOT (!): This operator flips the truth of a single condition. So, if the person DOES NOT earn $30,000, they don't qualify.
Let's look at some examples:
AND (&&):
- If one condition is true (e.g., earns $30,000) and the other is true (e.g., worked for 2 years), the whole expression is true.
- If one condition is false (e.g., earns $25,000) and the other is true (e.g., worked for 2 years), the whole expression is false.
OR (||):
- If one condition is true (e.g., earns $30,000) and the other is false (e.g., worked for 1 year), the whole expression is true.
- If both conditions are false (e.g., earns $25,000 and worked for 1 year), the whole expression is false.
NOT (!):
- If the condition is true (e.g., earns $30,000), the NOT operator makes it false.
- If the condition is false (e.g., earns $25,000), the NOT operator makes it true.
These logical operators are super helpful when you need to make complex decisions in your code. You can combine them to create even more intricate conditions, like "Earn at least $30,000 AND have worked for at least 2 years, OR have a college degree."
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/5cb154c6-1bb0-45f1-9c7a-954be3687468)
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/b8baffcd-5d6c-4cbd-ab60-d5c96e1c50db)
Logical operators in code using Java
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/d1baa631-364a-4d1b-8447-c7c884ee11b9)

### Short Circuit Logic
Excellent explanation! You really understand how the short-circuiting behavior of the logical AND and OR operators works in Java. Let me summarize the key points:
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/4165222b-b26e-4861-b742-92472826e64d)

AND (&&) Operator:
When using the AND operator, both conditions must be true for the overall expression to be true.
If the first condition is false, there's no need to evaluate the second condition, as the overall expression will be false regardless.
This is a shortcut that improves performance by avoiding unnecessary evaluations.
OR (||) Operator:
With the OR operator, only one of the conditions needs to be true for the overall expression to be true.
If the first condition is true, there's no need to evaluate the second condition, as the overall expression will be true regardless.
This is another shortcut that saves time by stopping the evaluation once a true condition is found.

You provided a great example to illustrate these concepts:
false && true // Evaluates to false, no need to check the second condition
true || false // Evaluates to true, no need to check the second condition
true && true // Both conditions are evaluated, as both need to be true
Recognizing and understanding this short-circuiting behavior is crucial for writing efficient and optimized code in Java. It allows you to avoid unnecessary computations and improve the overall performance of your applications.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/5b9a8e59-e8c1-4259-96eb-82ab682d377c)
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/848468de-8fea-47d0-955b-73ee4be355d2)


# Repetition Structures in Java
### While Loop
Loops are like a magical spell for code that makes it do the same thing again and again. So, when your code needs to do something over and over, it is smart to put it in a loop. That way, you do not have to keep copying and pasting the same stuff repeatedly.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/d2ec5c3d-8046-432e-bd7f-000aa6965cef)

Excellent explanation of how to use a `while` loop to validate user input and ensure it falls within the expected range! You've really captured the key points:
1. **Validating User Input**: When you need to ensure the user provides a valid input, such as hours worked within a specific range, a `while` loop is the perfect tool.
2. **Loop Condition**: The loop condition checks if the `hoursWorked` variable is outside the valid range (greater than 40 in this case). As long as the condition is true, the loop continues to execute.
3. **Updating the Input**: Inside the loop, you prompt the user to provide a new input, which is then stored in the `hoursWorked` variable. This ensures the loop condition can be reevaluated with the updated value.
4. **Avoiding Infinite Loops**: You emphasize the importance of making sure the loop condition variable (`hoursWorked`) can change within the loop. Otherwise, you risk an infinite loop that will never terminate.
Your step-by-step explanation, with the helpful analogies and examples, really drives home the power and utility of `while` loops for input validation. This is a crucial programming concept that you've explained very clearly.

### Do while loop
A do while loop is like a while loop, but it does the check after it runs, not before. So, It will run at least once. Keep in mind that do while loops are not used much because the regular while loop usually does the job. But it is handy to understand how do while works.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/6a78dd5b-09df-42b8-bad2-b7f06c8e28a1)
The problem at hand requires creating a program that allows the user to input a couple of numbers, calculates their sum, and displays the result. The program will continue running until the user chooses to stop.
To achieve this, we use a do-while loop. The loop starts with the "do" keyword and a pair of curly braces. Inside the braces, we include all the actions we want the loop to perform. After the braces, we add the "while" keyword and a condition inside parentheses, followed by a semicolon.
For this specific problem, the condition is based on whether the user wants to run the loop again. We create a variable called "runAgain" and initialize it to 0. If "runAgain" is equal to 1, it indicates the user wants to repeat the loop. Inside the loop, we prompt the user to enter the first and second numbers, which we store as "number1" and "number2". We then calculate the sum and display the result.
After the calculations, we ask the user if they want to run the loop again. If they enter "1" for "yes," we update the "runAgain" variable accordingly. If they enter "2" for "no," the loop terminates.
When the program runs, it immediately enters the do-while loop. The user can input numbers, and the loop will continue until the user chooses to stop.
The key distinction between do-while and regular while loops is that do-while loops execute the code at least once, regardless of the initial condition. This is useful in situations where you want to ensure the loop runs at least once before checking the condition.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/59c78fad-cccc-473a-ac27-ce9237fbac8c)

### For Loop
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/938abbd8-265c-4123-8d13-4162a4fb3a55)
The for loop is distinct from other types of loops because it is driven by a counter, rather than a condition. The for loop has a specific number of times it needs to execute its code. This makes it well-suited for situations where you need to perform a task a predetermined number of times.
For example, imagine you're creating a program for a cashier. The cashier needs to scan a number of items and calculate the total cost. The for loop is an excellent tool for this task, as it allows you to keep precise track of the item count as you tally up the total.
The structure of the for loop includes three main components:
The initialization, where you set the starting value of the counter variable.
The condition, which determines when the loop should stop executing.
The increment/decrement, which updates the counter variable after each iteration.
By having this well-defined structure, the for loop ensures that the code inside it runs a specific number of times, making it a powerful and flexible construct for a wide range of programming tasks that require counting or iterating over a known number of items.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/869b7859-66e3-409a-b357-f11a5ecbe02a)
### For loop key factors
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/4fa277ba-7bbf-4039-a96d-83acb1c8f327)

### Nested Loops
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/c01cedda-3b0f-474f-90b1-6efce2f88af8)

The outer for loop is used to iterate through each of the 24 students in the class. The loop control variable i is used to keep track of the current student.
For each student, there is an inner for loop that iterates through the 4 test scores for that student. The loop control variable j is used to keep track of the current test score.
Inside the inner loop, you:
Initialize a total variable to 0 to keep track of the sum of the student's test scores.
Prompt the user to enter the score for the current test (j+1).
Add the score to the total.
Once all 4 test scores have been entered, you calculate the average by dividing the total by 4 and print out the result for the current student (i+1).
The nested loop structure allows you to completely process each student's test scores before moving on to the next student, ensuring you have the necessary information to calculate the individual averages.
You note that the nested loop technique can be applied using different types of loops (e.g., while loops) depending on the specific requirements of the problem.
This is an excellent example of how nested loops can be used to tackle complex, multi-faceted problems in a structured and efficient manner. The step-by-step explanation makes it easy to understand the purpose and implementation of the nested loop approach.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/f8189e61-e441-40c6-928b-0be13b91a04c)

### Break Statements
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/deeaf54f-a361-4994-a8e5-6425b0bbc0b3)
The program sets up a for loop to iterate through each character in the input text. The loop control variable i is used to keep track of the current position in the text.
Inside the loop, the current character is retrieved using text.charAt(i) and stored in a variable called currentLetter.
The program then checks if currentLetter is equal to either an uppercase 'A' or a lowercase 'a'. If so, it sets a flag variable letterFound to true.
Here's the important part: Once the letter 'A' is found, there's no need to continue searching the rest of the text. So, the program uses the break statement to immediately exit the loop, regardless of whether the loop's normal termination condition has been met.
By using the break statement, the program can efficiently stop the loop as soon as the desired condition is met, without having to waste time iterating through the remaining characters in the text.
This is a great example of how the break statement can be a powerful tool for controlling the flow of a loop. It allows you to exit a loop prematurely, which can be especially useful when you've found the information you're looking for and don't need to continue the loop any further.
The ability to break out of a loop is an important concept in programming, as it gives you more flexibility in handling complex control flow scenarios. The break statement can be used in various types of loops, including for, while, and do-while loops, making it a versatile tool for problem-solving.
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/1b8134a2-0b8c-47e1-975b-e5ffc72a4c8f)

