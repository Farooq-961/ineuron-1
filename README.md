# ineuron- assignment-1

1. In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.

-87.8 

2. What is the difference between string and variable?

   String is a datatype which is used to store sequence of characters.
   Variable is an entity which is used to store values. values can be anything like str,int,float,etc 

3. Describe three different data types.

    There are 14 datatypes in Python
    Among them int,float,bool
    int -> int is used to store integer values. In other programming languages int has some limit or range if it exceeds it returns garbage value but in python, int does not any       limit or range we can store any int value 
    
   
4. What is an expression made up of? What do all expressions do?

    Expression is made up of operators(=,-,*,/,//,etc) and operands(operands can be string,int,float).
    Some value is evaluated using this expression
    
5. This assignment statements, like spam = 10. What is the difference between an expression and a statement?
    Expression is combination of operands and operators and it evaluates some value.
    Statement is a single of code which doesn't evaluate any value. 

6. After running the following code, what does the variable bacon contain?
bacon = 22
bacon + 1

After running code the variable bacon contains 23

7. What should the values of the following two terms be?
'spam' + 'spamspam'  ---> 'spamspamspam'
'spam' * 3  ---->'spamspamspam'(spam is multiplied by 3 )

8. Why is eggs a valid variable name while 100 is invalid?
  From Python identifier rules any variable name should start with _ or __ or alphabets 


9. What three functions can be used to get the integer, floating-point number, or string version of a value?
   
   int() --> can be used to get integer
   float() --> can be used to floating point number
   str() --> can be used to get string values
   
10. Why does this expression cause an error? How can you fix it?
'I have eaten ' + 99 + ' burritos.'
 We can concate only strings but intergers therefore it returns error "TypeError: can only concatenate str (not "int") to str"
