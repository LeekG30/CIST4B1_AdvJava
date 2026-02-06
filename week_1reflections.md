This week I learned about the components of recursion which involves: a base case, a recursive step, and the call stack. 
The first (Base case) is the condition that stops the recursion by solving the simplest version of the problem.
It prevents infinite loops and StackOverFlowError, by not calling the method again

The second (recursive Step) is where the method calls itself, but with a modified argument that is smaller and closer to the base case.
Shrinks the problem with each step, which ensures the code eventually hits base case.

Last (call stack)- recursion relies on the system's memory stack to keep track of every function call.
Pushes a new frame for every recursive call and then pops them off one by one.
This calculates the result once the base case is reached.
