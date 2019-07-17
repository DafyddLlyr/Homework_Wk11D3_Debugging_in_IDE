## Introduction to Debugging in IDE

Answer the following questions:

1. What is the purpose of a breakpoint?
*A breakpoint allows us to stop the code from executing at a particular point. This means that we can access variables at a certain point in the execution of the code in order to evaluate them and work out why it is not behaving as expected.*


2. Does the line of code on a breakpoint run when you start debugging?
*When using breakpoints in IntelliJ the line of code selected as the breakpoint does not run, it breaks immediately before the execution of that line of code.*


3. How do we debug the next line of code?
*In order to debug the next line of code and to move along we need to use the "Step Over" button. This executes the current line of code and breaks once it has executed.*



4. What does the step into command do?
*The "Step Into" command will take us to the method currently being called at the breakpoint, allowing us to go through the method step by step to evaluate the problem.*



5. What is the difference between evaluate expression and evaluate code fragment?
*Evaluate expression allows us to execute a single line snippet of code at the breakpoint - this could allow us to see what a particular method or property return. Semi-colons are not required and will not allow the code to execute. Evaluate code is similar, but allows us to execute multiple lines of code and store variables in order to solve the problem. Semi-colons at the end of each line are required and the code will not execute correctly without this.*
