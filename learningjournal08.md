# Learning Journal 08
Comparison operators: evaluating conditions
Evaluate by comparing one value in the script to what you expect it might be
Result is boolean (T or F)
== is equal to
!= not equal to
=== strict equal to (the preferred method)
Same data type AND value
!== strict not equal
Logical operators
&& logical and
|| logical or
! logical not
Loops
Check a condition
If true, code block runs
Will check condition again to see if still true, etc. 
Will repeat until condition returns false
3 types
For
When you want to run code a specific number of times 
Condition is usually a counter telling it how many times to run the loop
for (var i = 0; i <10; i++) {
document.write(i);
}

The for loop above shows the variable i being initialized, given a condition, and given instructions on how to update all in one line (var i is 0 and if var i is less than 10 then increment it by one...do this until i is no longer less than 10)
Often used to loop through items in an array
While
If you’re not sure how many times the code will need to run
Condition can be something other than a counter because the code will continue to loop until the condition is false
Var i = 1; 
Var msg = ‘ ‘;
While (i < 10) {
	Msg += i + ‘ x 5 = ‘ + (i * 5) + ‘<br />’; i++}
document.getElementById(‘answer’).innerHTML = msg;
Do while
It will always run the statement inside the curly braces at least once even if condition evaluates to false
Keywords
Break
Makes the loop terminate and tells interpreter to move onto the next statement of code
Continue
Tells interpreter to continue with current iteration and check condition again (if true, will run the code again)
Infinite loop 
If the condition never returns false
