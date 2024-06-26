# Java-basics
# Module 1 - Introduction to Java
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

# Methods in Java
### Creating Methods
In Java, methods are akin to tools within a class. They enable us to break down complex problems into smaller, more manageable components. Methods perform specific tasks and help us avoid redundancy in our code. In other programming languages, these constructs may be referred to by different names, such as functions or modules, but in the context of Java, we refer to them as methods.

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/5f766128-4927-4612-8a63-1f897723a111)

Header: The opening line of the method, which acts as an "ID card" for the method. It includes:
Access modifier (e.g., public) - determines who can use the method
Optional modifiers (e.g., static, final)
Return type (e.g., int) - specifies the type of value the method returns
Method name (e.g., calculateSum) - should start with a verb and be descriptive
Parameter list enclosed in parentheses - lists the inputs the method requires
Signature: The combination of the method's name and its parameter list, which uniquely identifies the method.
Body: The actual code inside the curly braces that defines the method's functionality.
Return Statement: If the method has a non-void return type, it must include a return statement at the end to send the result back.
The key purpose of methods is to break down complex problems into smaller, more manageable parts, and to avoid code duplication by encapsulating specific tasks or calculations. The method header provides information about how to use the method, while the body contains the implementation details.

### Calling Methods
Okay, let's break down the key points about how to use methods in a Java program:
1. **Methods don't execute automatically**: Methods need to be explicitly called or "summoned" in order to run their code. They don't spring into action on their own.
2. **Placing methods within a class**: All methods must be defined within the scope of a class. The order in which the methods are written does not matter, as long as they are properly defined.
3. **Calling methods from the main method**: When a Java program starts, the execution begins in the `main()` method. From the `main()` method, you can call other methods by using the method's name followed by empty parentheses and a semicolon.
4. **Example of the `greetUser()` method**: This method likely prompts the user for their name, stores it in a variable, and then prints a greeting using that name. However, this method won't run until it is called from the `main()` method or another method.
5. **Calling the `greetUser()` method**: To execute the `greetUser()` method, you would write `greetUser();` within the `main()` method or another method. This "summons" the `greetUser()` method and causes it to run its internal code.
The key takeaway is that methods are like tools or functions that can be called upon to perform specific tasks, but they require explicit invocation from the main program flow (typically the `main()` method) in order to execute. The order of method definitions does not matter, but the order in which they are called is what determines the program's behavior.

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/0c0cfacd-90ef-4882-9ca6-770895e8f6db)

### Variable scope

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/7de58bac-2f17-438e-80b5-b9c985c61d93)

1. **Method Execution**: Methods do not execute automatically - they need to be explicitly called, typically from the `main()` method or another method.
2. **Method Scope**: All methods must be defined within a class. The order of method definitions does not matter, as long as they are properly structured.
3. **Variable Scope**:
   - Local variables: Variables defined within a specific method or block of code. They can only be accessed within their defined scope.
   - Global (or class-level) variables: Variables defined at the class level, outside of any methods. They can be accessed from anywhere within the class.
   - Variable name reuse: You can have variables with the same name in different scopes, and they will be treated as separate variables.
   - Local variable precedence: When a local variable and a global variable have the same name, the local variable takes precedence within its scope.
   - Accessing global variables: To explicitly access a global variable from within a local scope, you can use the `this` keyword, e.g., `this.myVariable`.
4. **Variable Scope Considerations**:
   - Use local variables when the variable is only needed within a limited scope.
   - Use global variables when the variable needs to be accessed across multiple methods.

### Passing Data to Methods

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/6d952dcd-9ea2-4b44-8d08-c0407f90a140)

Method Parameters:
Methods can require external data to perform their tasks.
This data is passed to the method through a list of parameters defined in the method signature.
Each parameter has a data type and a name, e.g., int creditScore and double salary.
Accessing External Data:
The variables defined in the main method (e.g., actualSalary and actualCreditScore) are not directly accessible by the isUserQualified method.
By including the parameters in the isUserQualified method signature, the method can now access and use the external data.
Passing Arguments:
When calling the isUserQualified method from the main method, you pass the arguments (e.g., actualSalary and actualCreditScore) that correspond to the parameters in the method signature.
The order of the arguments must match the order of the parameters in the method signature.
Variable Naming:
The variable names in the main method and the isUserQualified method can be different (e.g., actualSalary vs. salary), as they are in different scopes.
This demonstrates that the method parameters create a new scope within the method, separate from the scope of the main method.
This is a great example of how methods can leverage external data through parameters to perform their specific tasks. The parameter list acts as a bridge, allowing the method to access the necessary information from the main program flow.

### Returning Data from methods

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/de2391e4-4cb4-454a-86a1-66f2e2a24d34)

Methods can perform actions and sometimes return values.
The isUserQualified method currently doesn't return anything, so it's like a one-way street.
To make it return a value, we change its return type to boolean. It will return true if the user is qualified, and false otherwise.
When we call a method that returns a value, we can store that value in a variable. In this case, we'll call the variable qualified.
The notifyUser method wants a boolean value (a yes or no) when we call it. It will then use that value to determine the appropriate message to display.
When we run the code, the qualified variable will hold the result from isUserQualified, and notifyUser will use that value to print the correct message, like "Sorry, you have been declined" if qualified is false.
This flow of passing values between methods is similar to following a flowchart.
The main idea is to transform the isUserQualified method to return a boolean value, capture that value in a variable, and then use that variable in the notifyUser method to provide the appropriate feedback to the user.

### Overloading Methods
In a class, you can have multiple methods with the same name but different parameters. This is called method overloading. In the "month" class, there are two "getMonth" methods - one that takes an integer representing the month, and another that takes a string with the month's name. This is perfectly valid, and you can overload as many methods as needed, as long as their parameter lists differ.
The way the compiler determines which overloaded method to use is by looking at the arguments you pass when calling the method. It will match the provided arguments to the method's parameter list.
If you try to create overloaded methods with the exact same parameter list, you'll get a compilation error, because the compiler won't be able to differentiate between them.
For example, adding a third "getMonth" method that takes a string parameter, but with a different parameter name, would still result in an error, because it has the same signature as the second method.
Overloading methods is a convenient way to provide similar functionality with slight variations, without having to rely on complex conditional logic within a single method. It leads to cleaner, more organized code.

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/2d174d4a-7152-4672-93a8-54cde176aeb8)

# Objects in Java
### Defining classes for objects

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/b7dfee56-d0e9-433c-9586-2a2442c6b299)

In programming, objects are like containers that hold both data and actions. You can use these data and actions in different parts of your code by creating an object, similar to how you'd build a blueprint for a rectangle with all its features.
Thinking of a rectangle as a class, it has characteristics or "fields" that define it, like a length and a width. These fields are the rectangle's identifying properties.
The actions you can perform on a rectangle, like measuring its perimeter and area, are called "methods". These methods perform the calculations to determine the rectangle's measurements.
The class itself is just a blueprint - it doesn't have any specific values for the length and width. To use a rectangle, you need to create an instance of the class and set the values for its fields. This is where "getter" and "setter" methods come into play, allowing you to retrieve and modify the rectangle's dimensions.
In object-oriented programming, there is a concept called "encapsulation", which states that a class's data (fields) should be kept private, while the methods that define its behavior can be made public. This ensures that the internal implementation of the class is hidden and can only be accessed through the provided methods.
Additionally, there is an "access modifier" called "protected", which allows classes within the same package to access the class's members, similar to having no access modifier at all.
The rectangle class you're building is like a blueprint - it defines the structure and behavior of a rectangle object, but the specific values for length and width are set when you create an instance of the class.

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/e6673035-2b1c-40cc-931a-156f106b8c89)

### Java Constructors

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/7abea6be-9dea-4d9c-a2c9-98a5ab58e30a)

In addition to using setter methods, you can also set a class's field values using a constructor. Constructors are a convenient way to give an object its initial values or configure its state when it's created.
Every object has a constructor, and the default constructor is the most basic type you'll encounter. A default constructor doesn't take any parameters. It's useful when you want to create a new object but don't have the specific values for its fields yet. The default constructor will set some default values for the object's fields.
In Java, the default constructor is always present, even if you don't explicitly define it. It's an empty constructor that doesn't do much, but it's there as a hidden feature.
Let's break down the structure of a constructor:
- It starts with an access modifier like "public"
- It has the same name as the class it belongs to
- It doesn't have a return type, even though it acts like a method
- It may have parameters inside the parentheses, but the default constructor doesn't have any
- The constructor's body is contained within curly braces
The purpose of the default constructor is to set default values for the class's fields. In the case of a rectangle, we might set the length and width to zero.
You can actually have multiple constructors for a class, all with the same name but accepting different parameters. For example, you could create another constructor that takes the length and width as parameters, and then uses the setter methods to assign those values to the fields.
Having multiple constructors gives you options for how to set up the initial state of an object when it's created, whether you know the specific field values upfront or need to use default values.

### Object Instantiation

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/37b21030-b4a1-4b51-afc8-213bc9b209b2)

In this scenario, we will create two Rectangle objects to calculate the areas of different rooms. We'll do this within the HomeAreaCalculator class.
To create a new object, we need to instantiate a class. In this case, we want a "room" object that is based on the Rectangle class. Objects use classes as their data types, so our object type will be Rectangle.
We'll name the first object "room1". To create it, we use the "new" keyword followed by the class constructor. We'll use the default constructor with no parameters.
We can access the object's methods using the dot operator. For room1, we'll set the width to 25 and the length to 50, then calculate the area by calling room1.calculateArea().
Next, we'll create a second room object called "room2". This time, we'll use the constructor that takes length and width parameters, passing in values of 30 and 75.
The Rectangle class serves as a reusable blueprint that we can use to model different types of rectangles, in this case representing rooms in a house. The class itself doesn't care how we use it - it simply provides the structure and functionality we need.

### Method parameters as objects

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/6402dbd4-db0f-4e87-a156-0b349848060d)

Objects can be used as method arguments, just like primitive data types. For example, we have two Rectangle objects representing rooms - a kitchen and a bathroom. We created these objects by calling the Rectangle constructor and providing the length and width values.
To calculate the total area of these two rooms, we create a method called calculateTotalArea. This method returns a double and takes two Rectangle objects as input parameters. We declare it as public static double calculateTotalArea(Rectangle rectangle1, Rectangle rectangle2).
Inside the calculateTotalArea method, we use the dot operator to call the calculateArea() method on each of the Rectangle objects passed in as arguments. We then return the sum of their areas: return rectangle1.calculateArea() + rectangle2.calculateArea().
In our main method, we call the calculateTotalArea method, passing in the kitchen and bathroom Rectangle objects as arguments, like this: double totalArea = calculateTotalArea(kitchen, bathroom).
Finally, we print the total area with a message like "The total area is [totalArea]".

### Method Return Types
Imagine we want to create a method that returns both the length and width of a rectangle. However, methods can only return one thing at a time. To work around this, we can make the method return an object that encapsulates both the length and width.
Instead of creating the kitchen and bathroom objects directly with fixed length and width values, we will use a new method called getRoom(). This method will ask the user for the length and width, and then it will create and return a new Rectangle object with those dimensions.
The getRoom() method will have a return type of Rectangle, and inside the method, we will create a new Rectangle object using the length and width provided by the user, and then return that object. We don't need to store the Rectangle object in a local variable inside getRoom() - we can simply return it directly.
In the main method, we will call getRoom() to create the kitchen and bathroom objects. For the kitchen, we'll use length 200 and width 400, and for the bathroom, we'll use length 300 and width 700.
The key point here is that by returning an object from the getRoom() method, we can encapsulate multiple pieces of information (the length and width) and pass them back to the main method, where we can then use those Rectangle objects as needed.

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/41780156-0865-4658-871b-06607c86330a)

### Wrapper Classes

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/735ed11c-f1a8-4faf-bf01-4b098358e5c3)

Wrapper classes provide a way to turn primitive data types into objects. For example, we have two variables: number1 (an int primitive) and number2 (an Integer object, which is the wrapper class for the int type).
The benefit of using wrapper classes like Integer is that they provide a variety of useful methods and properties that are not available with the primitive data types. These wrapper classes exist for all the basic data types in Java.
Let's look at the Integer wrapper class in more detail. It acts as a toolbox for working with integer values. It provides constants like MIN_VALUE and MAX_VALUE that tell you the smallest and largest possible int values. It also has methods like compare() and compareTo() that help you compare integer values.
Additionally, the Integer class has conversion methods like doubleValue() and floatValue() that let you convert an Integer object to other numeric data types. One particularly useful method is parseInt(), which can convert a string of numbers into an actual int value.
If you ever need to take a primitive int variable and turn it into an Integer object, you can use the valueOf() method. Similar wrapper class capabilities exist for the other primitive data types in Java as well.
The key benefit of wrapper classes is that they extend the functionality of primitive data types by providing a richer set of methods and properties to work with.

### Records

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/9b00ab22-abb3-4b75-bfd1-7db8d3629ba7)

Records are a new feature in Java that provide a simpler way to create simple data-carrying objects, similar to Java classes. Instead of defining a full class with fields, getters, setters, and other methods, you can use a record to quickly define an object with just the necessary fields.
To create a record, you use the record keyword instead of class, and you list the fields inside parentheses, just like in a constructor. The record automatically generates the necessary getter methods for those fields, so you don't have to write them yourself.
You can also add your own custom methods inside the curly braces of the record definition, if needed. This allows you to add additional functionality beyond just the basic fields.
Creating instances of a record is very similar to creating instances of a class. You use the new keyword followed by the record name, and pass in the necessary field values through the constructor.
The key difference with records is that they are immutable - once you create a record instance and set its field values, those values cannot be changed. Records don't have setter methods like classes do.
Records are particularly useful for creating simple "plain old Java objects" (POJOs) - basic data-carrying objects where you just need to store and access some values. The record syntax provides a more concise and streamlined way to define these types of simple objects, compared to writing a full class.
In summary, records offer a lightweight alternative to classes when you need to model simple data-centric objects, providing automatic generation of common methods while enforcing immutability.

# Module 2 - Java Fundamentals
### topics covered:
Inheritance, Polymorphism, Abstraction, Interfaces, Data Structures, Functional-programming, Exception handling

### Inheritance

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/c1dff0db-a9d5-479a-9eec-40f540e66bbe)

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/34004df6-4c12-4fae-a678-9b445f8447cc)


Inheritance is a fundamental concept in object-oriented programming where a new class acquires the properties and behaviors of an existing class. It creates a hierarchical relationship between the classes involved.

In an inheritance relationship, there are two main participants:

The parent class (also called the superclass or base class): This is the existing class that provides the attributes and methods to be inherited.
The child class (also called the subclass or derived class): This is the new class that inherits from the parent class. It gains access to all the public and protected members of the parent class.
The child class essentially becomes an extension of the parent class, inheriting all its characteristics. This allows the child class to reuse the code and functionality of the parent class, without having to reimplement it from scratch.

Inheritance establishes a "is-a" relationship between the parent and child classes. For example, if "Vehicle" is the parent class, a "Car" class that inherits from it would be considered a type of Vehicle.

The key benefit of inheritance is code reuse and the ability to build upon existing functionality to create more specialized classes. It's a powerful mechanism for organizing and structuring object-oriented programs.

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/8e390c72-f502-4d90-8c54-cbde91c43949)

We have this 'Person' class that has stuff like 'name,' 'age,' and 'gender,' and then we have methods to get and set those. If we want to make an 'Employee' class that is like 'Person,' but with extra information for employees, we use the keyword 'extends' in the 'Employee' class header. 
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/666e5931-87ca-46af-a78a-b8bef18777f3)
In this InheritanceChecker class, there is a person object and an employee object. When we use the dot operator with "person", we can access the getter and setter methods for age, gender, and name. However, with "employee", not only do we get those methods from the Person class, but we also get the methods defined in the Employee class. 

### Constructors in inhertance

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/e02de8cc-2aca-40cc-b4ac-6adcb44a082f)

When dealing with constructors and inheritance, there are some important considerations to keep in mind.
Suppose you have a 'Person' class with a default constructor that prints "in-person default constructor", and an 'Employee' class that inherits from 'Person' and has a default constructor that prints "in-employee default constructor". When you create a new instance of the 'Employee' class, the constructor of the 'Person' superclass is called first, and then the 'Employee' subclass constructor is executed.
This happens because when a class inherits from another, the superclass constructor needs to be properly initialized before the subclass can use it. The subclass constructor doesn't explicitly call the superclass constructor, but the Java runtime ensures the superclass is set up first.
If you want to call a specific constructor in the superclass, you can do so using the super() keyword in the subclass constructor. This must be the very first statement in the subclass constructor, as Java requires the superclass to be initialized before the subclass can do anything else.
For example, if the 'Person' class has a constructor that takes a name parameter, you can call that constructor from the 'Employee' class using super(name). This allows you to choose which superclass constructor to use, rather than relying on the default.
Furthermore, if the superclass doesn't have a default constructor, the subclass must explicitly call one of the superclass's other constructors using super(). If you don't do this, the Java compiler will throw an error.

Superclass constructors are called before subclass constructors, by default.
You can explicitly call a specific superclass constructor using super().
The super() call must be the first statement in the subclass constructor.
If the superclass has no default constructor, the subclass must call one of the superclass's other constructors.

### Overriding and Overloading inherited methods

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/980132ec-0bbb-45d9-a5dd-641376f99847)

When you have a subclass, it automatically inherits all the members (fields and methods) from its superclass. Sometimes, the subclass may want to modify the behavior of a particular method that it inherited. This is called "overriding" a method.
For example, let's say we have a "Rectangle" class and a "Square" class that inherits from it. The "Rectangle" class has a "calculatePerimeter()" method that works for rectangles. However, the way to calculate the perimeter of a square is different, so the "Square" class needs to override that method to use the correct formula.
To override a method, you create a new method in the subclass with the same name and signature (i.e., the same parameters and return type) as the method in the superclass. You then implement the method body with the desired behavior for the subclass.
The subclass can access any protected or public members (fields and methods) from the superclass, so it can use those in the overridden method.
It's a good practice to use the "@Override" annotation when overriding a method. This tells Java that you're intentionally replacing the superclass method, which helps avoid mistakes.
Another concept is "method overloading," which is when a class has multiple methods with the same name but different parameters. This is different from overriding, where you're modifying the behavior of an inherited method.
For example, in the "Rectangle" class, you might have a "print()" method that simply prints "I am a rectangle." In the "Square" class, you could have a different "print()" method that takes a string parameter and prints "I am a [what]."
When you call the "print()" method on an object of the "Square" class, Java will choose the appropriate overloaded version based on the arguments you provide.

In summary:
Overriding: Modifying the behavior of an inherited method by providing a new implementation in the subclass.
Overloading: Providing multiple methods with the same name but different parameters in the same class.
Overriding uses the same method name and signature, while overloading uses the same name with different parameters.

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/0b49b393-ee7f-4bd7-8475-95a91df80193)

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/e26e68ee-73f2-4d90-959f-3281e76834e0)

![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/013dbab3-499a-445d-8232-ed6fbe3dd9e0)

### Chain of Inheritance 
![image](https://github.com/McengwaAyanda/Java-basics/assets/81769629/6f538028-dfd2-44dd-b5a6-337cb426976f)

