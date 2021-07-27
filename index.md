javascript-best-practices

1. Make it understandable: Choose easy to understand and short names for variables and functions.

2. Avoid Globals: Global variables are a terribly bad idea.
Reason: You run the danger of your code being overwritten by any other JavaScript added to the page after yours.
Workaround: use closures and the module pattern

3. Stick to a Strict Coding Style: Browsers are very forgiving JavaScript parsers. However, lax coding style will hurt you when you shift to another environment or hand over to another developer. Valid code is secure code.

4. Comment as Much as Needed but Not More
“Good code explains itself” is an arrogant myth.
Comment what you consider needed - but don’t tell others your life story.

5. Always Declare Local Variables
All variables used in a function should be declared as local variables.
Local variables must be declared with the var keyword or the let keyword, otherwise they will become global variables.

6. Declarations on Top
It is a good coding practice to put all declarations at the top of each script or function.

7. Declare Arrays with const:
Declaring arrays with const will prevent any accidential change of type

8. Use === Instead of ==
JavaScript uses two different kinds of equality operators: === and !== are the strict equality operators, while ==  and != are the non-strict operators. It is considered best practice to always use strict equality when comparing.

9. Use JSLint
JSLint is a debugger written by Douglas Crockford. Simply paste in your script, and it'll quickly scan for any noticeable issues and errors in your code.

10. Place Scripts at the Bottom of Your Page
This tip has already been recommended in the previous article in this series. As it's highly appropriate, though, I'll paste in the information.


Sources:
1. https://www.thinkful.com/learn/javascript-best-practices-1/
2. https://www.w3schools.com/js/js_best_practices.asp
3. https://code.tutsplus.com/tutorials/24-javascript-best-practices-for-beginners--net-5399