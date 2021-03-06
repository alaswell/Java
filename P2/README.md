 CS 160, Summer 2015
Programming Assignment P2
Numbers and Strings

Programming due Monday, June 22nd at 12 noon; Late deadline June 22nd at 10 p.m.
Using Numbers and Strings in Java
This programming assignment has four objectives:

    to use Java variables and operators to write expressions,
    to understand how to manipulate Java strings and characters,
    to print formatted output, and
    to see if you can follow a specification exactly! 

Description
The program 1) declares a set of variables of several different data types, 2) uses the variables to construct expressions to do some simple math, 3) manipulates strings and characters, and 4) outputs the results.

Instructions
For this assignment, you must follow directions exactly. Create a P2 project in Eclipse then write a class P2 with a main method, and put all of the following code into the main method:

    Declare an integer variable of type byte, short, int, and long.
    Declare a floating-point variable of type float, and double.
    Declare three variables of type char.
    Declare three instance variables of the class String.
    Initialize the variables using an initializer or assignment statement:
    byte: 97, short: 24567, int: 113355, long: 9384876238
    float: 1.57, double: 23.456
    char: '$', 'H', '3'
    String: "Java", "Programming", "Great"
    NOTE: The long integer value exceeds 32-bits, and therefore requires special syntax.
    NOTE: The float value similarly requires special syntax, otherwise it will default to type double.
    Find the syntax referenced above for long and float literals on the web and use them.
    (Line 1) Print the four integer values in the following order (byte,short,int,long) separated by commas.
    (Line 2) Print the two floating-point values in the following order (float, double) separated by colons.
    (Line 3) Print the sum of all the integer variables divided by 1000.
    (Line 4) Print the square root of the sum of all the floating-point variables.
    NOTE: You may use Math.sqrt() to compute the square root.
    (Line 5) Print the quotient of the double variable divided by the int.
    (Line 6) Print the three characters, separated by semicolons.
    (Line 7) Increment all three character values and print them again, separated by periods.
    (Line 8) Using the three String variables and string constants, print Java Programming is Great!.
    NOTE: The following items require a String method call inside a print statement.
    (Line 9) Print the length of all three String variables, separated by commas.
    (Line 10) Print the third String variable in uppercase letters.
    (Line 11) Print the third through sixth characters of the second String variable.
    (Line 12) Print the index of the character 'v' in the first String variable.
    (Line 13) Print the fourth character of the second String variable. 

Sample output
Your program should match the output shown below, with no mispellings, wrong characters, incorrect case, or extra white space! A missing line will cause many errors, so make sure you have all of the lines below in the correct order. See the grading criteria below.

97,24567,113355,9384876238
1.57:23.456
9385014
5.002599329593775
2.0692514666313793E-4
$;H;3
%.I.4
Java Programming is Great!
4,11,5
GREAT
ogra
2
g

Specifications
Your program must meet the following specifications:

    Work on your own, as always.
    The name of the source code file must be exactly P2.java.
    Name the file exactly - upper and lower case matters!
    Comments at the top as shown in P1.
    Assignments should be implemented using Eclipse.
    Assignments should be implemented using Java 1.5 or 1.6 or 1.7.
    Make sure your code runs on machines in the COMCS 120 lab.
    Submit your program to the Checkin tab as you were shown in the recitation.
    Read the syllabus for the late policy.
    We will be checking programs for plagiarism, so please don't copy from anyone else. 

Grading Criteria

    100 points for perfect submission.
    0 points for no submission, will not compile, submitted class file, etc.
    Preliminary Tests
        testCompile: checks that program compiles. (10 points)
        testComment: checks the comment block at top of program. (10 points)
        test1: checks the first line of output. (5 points)
        test2: checks the second line of output. (5 points)
        test3: checks the third line of output. (5 points)
        test4: checks the fourth line of output. (5 points)
        test5: checks the fifth line of output. (5 points)
        test6: checks the sixth line of output. (5 points)
        test7: checks the seventh line of output. (5 points)
        test8: checks the eighth line of output. (5 points) 
    Final Tests
        test9: checks the ninth line of output. (8 points)
        test10: checks the tenth line of output. (8 points)
        test11: checks the eleventh line of output. (8 points)
        test12: checks the twelfth line of output. (8 points)
        test13: checks the thirteenth line of output. (8 points) 
    Preliminary testing only checks the first through eighth lines
    Final grading checks the remaining lines, and includes the preliminary tests. 

Submit your program to the Checkin tab on the course website, as you were shown in the recitation, and read the syllabus for the late policy (if necessary).

