Statements and Expressions
==========================

>Statements such as __if__ and __for__ can be used in two ways in JavaScript, with curly braces for multiple contained lines or without curly braces for one contained line. 

	// Good

>An overwhelming majority of JavaScript developers are in agreement that block state- ments should always use braces and always occupy multiple lines instead of one. This is because of the confusion created when braces aren’t included. 

Braces should be used for all block statements, including:






The second style of brace alignment places the opening brace on the line following the beginning of the block statement, as in this example:




	
	//1

	if (condition) { 
		doSomething();
	if ( condition ) { 
		doSomething();




	//1



>* Each case statement is indented one level from the switch keyword.


**As with other aspects of coding style, this choice is completely a matter of preference.**



####3.3 default

My preference is to omit default when there is no default action and annotate it using a comment, as in this example:



##3.The with Statement

>__The with statement is actually disallowed in strict mode__, causing a syntax error and indicating the ECMAScript committee’s belief that with should no longer be used.


##4.The for Loop


