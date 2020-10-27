### Top 10 things to Remember Day 3 
#### [Python Programming Basics]()

##### Chapter 2 : Flow Control (Continied) | Elements of Flow Control

Flow control statements often start with a part called the condition, and all are followed by a block of code called the clause.

 1. Conditions always evaluate down to a Boolean value(True/False).

 2.  Lines of Python code can be grouped together in blocks. You can tell when a block begins and ends from the indentation of the lines of code. There are three rules for blocks.
     - Blocks begin when the indentation increases.
     - Blocks can contain other blocks.
     - Blocks end when the indentation decreases to zero or to a containing block’s indentation.

 3. if Statements : An if statement’s clause (that is, the block following the if statement) will execute if the statement’s condition is True . The clause is skipped if the condition is False . It consisits of 
     - The if keyword
     - A condition (that is,an expression that evaluates to True or False)
     - A colon
     - Starting on the next line, an indented block of code (called the if clause)

4. else Statements : An if clause can optionally be followed by an else statement. The else clause is executed only when the if statement’s condition is False .An else statement doesn’t have a condition. It consists of 
     - The else keyword
     - A colon
     - Starting on the next line, an indented block of code (called the else clause)

5. elif Statements : While only one of the if or else clauses will execute, you may have a case where you want one of many possible clauses to execute. The elif statement is an “else if” statement that always follows an if or another elif statement. It provides another condition that is checked only if any of the previous conditions were False . It consists of 
     - The elif keyword
     - A condition (that is, an expression that evaluates to True or False )
     - A colon
     - Starting on the next line, an indented block of code (called the elif clause)
Note: For elif Statements the order matters!

6. while Loop Statements : You can make a block of code execute over and over again with a while statement. The code in a while clause will be executed as long as the while statement’s condition is True. It consists of 
     - The while keyword
     - A condition (that is, an expression that evaluates to True or False )
     - A colon
     - Starting on the next line, an indented block of code (called the while clause)
You can see that a while statement looks similar to an if statement. The difference is in how they behave. At the end of an if clause, the program execution continues after the if statement. But at the end of a while clause, the program execution jumps back to the start of the while statement. The while clause is often called the while loop or just the loop.

7. break Statements : There is a shortcut to getting the program execution to break out of a while loop’s clause early. If the execution reaches a break statement, it immediately exits the while loop’s clause. It consisits of 
     - The break keyword (only)

8. continue Statements : Like break statements, continue statements are used inside loops. When the program execution reaches a continue statement, the program execution immediately jumps back to the start of the loop and reevaluates the loop’s condition. (This is also what happens when the execution reaches the end of the loop). It consists of 
     - The continue keyword (only)

9. for Loops and the range() Function : The while loop keeps looping while its condition is True (which is the reason for its name), but what if you want to execute a block of code only a certain
number of times? You can do this with a for loop statement and the range() function. It consists of 
      - The for keyword
      - A variable name
      - The in keyword
      - A call to the range() method with up to three integers passed to it
      - A colon
      - Starting on the next line, an indented block of code (called the for clause).
You can use break and continue statements inside for loops as well. The continue statement will continue to the next value of the for loop’s counter, as if the program execution had reached the end of the loop and returned to the start. In fact, you can use continue and break statements only inside while and for loops. If you try to use these statements elsewhere, Python will give you an error.

10. importing modules : All Python programs can call a basic set of functions called built-in ­functions, including the print() , input() , and len() functions you’ve seen before. Python
also comes with a set of modules called the standard library. Each module is a Python program that contains a related group of functions that can be embedded in your programs.Before you can use the functions in a module, you must import the module with an import statement. In code, an import statement consists of the following:
      - The import keyword
      - The name of the module
      - Optionally, more module names, as long as they are separated by commas