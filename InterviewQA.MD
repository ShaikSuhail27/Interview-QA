
1.how to use the linux command inside the shell script?
ANS:we need to store the value like the command $() and store in some variable
Example:DATE=$(date)
Here DATE is the varibale , date is the linux command

2.what is exit status?
ANS:if we get any error in shell script by default it will not stop and we are responsible for stopping if we get any error through 
exit command

$?-->0--> if it is zero the previous command was success 
$?-->(1-127)-->if it is not equal to zero or else between the range from 1 to 127 then the previous command was failure

So if we face any error we are exiting the command through Exit (1-127)

3.SHIBANG (#!/bin/bash)
Ans: it is used to execute the script in the linux server

4.what are special variables?
ANs: variables are generally used to store the value.
The special variables are
1.$@---> all the arguments
2.$#--> no of variables
3.$0--> to return the script name

5.

