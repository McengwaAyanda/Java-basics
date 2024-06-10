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

### If-else Statements
A decision structure called an if-else statement enables a computer to follow one of two routes based on whether a particular condition is satisfied. An if-else statement, for instance, could be used by a software to ascertain whether a salesman has reached their quota. A congrats message might print from the application once the salesperson has reached their quota. If not, the software can print a warning telling the salesman to give it more the next time.
This code determines if the user's quota was reached. They were told if they did. If not, they are informed of the number of sales they missed.
The quota is originally initialized to 10 by the code. Next, it inquires about the user's weekly sales total. It then determines whether the sales are higher.

### If-else-if statements\
Imagine you're at school and you just took a test. The teacher is going to give you a grade, and there are 5 different grades you can get: A, B, C, D, or F.
The teacher is going to use a special tool called an "if-else-if statement" to figure out what grade to give you.
First, the teacher checks if your score is less than 60. If it is, they'll give you an F.
If your score is not less than 60, the teacher checks if it's less than 70. If it is, they'll give you a D.
If your score is not less than 70, the teacher checks if it's less than 80. If it is, they'll give you a C.
If your score is not less than 80, the teacher checks if it's less than 90. If it is, they'll give you a B.
If your score is not less than 90, the teacher will give you an A.
This "if-else-if" tool helps the teacher look at all the different possible scores and decide which grade is the right one for you. It's kind of like a big decision tree, with different branches for each possible grade.

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
