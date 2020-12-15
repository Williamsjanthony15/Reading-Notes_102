# **Day-7-Notes.md**
[Go Home](/README.md)



Notes for Day 7 "Scripting with Java Script"

due today

Lab
reading
review 


functions
expressions
how to identify usage in code

Funtions

Declare the function --
Function sayHello() {
    document.write('hello')
}
// Function = The Worker
// Sayhello() = The Nickname 
// { } = anything inside is the JOB
// Document.write = ties it to HTML
// ('hello') is what the job is.. 

THan you have to CALL the Function 
THe function call is defined by what you defined it as.... function ..... 

 function >>sayHello()<<
sayHello();

Expressions are one Liners
one variable = one value

Function = could have a bunch of code but they are supposed to end and work for the same endpoint.

Parameter and Arguments 

Parameter refers to the variable as  found in teh FUNCTION definition. Use it for declaring a function

Arguement refers to the actual input supplied at the function CALL.. 

Parameter defines the function 

Argument is the function
//Paramneter: name of variable to be used inside the function

msg is the parameter to the function
funcition sayMessage(msg) {
  
    alert(msg); // msg is an argument for alert. 

}

function add(a, b) {
    var result = a + b;
    
}

//Call function 

add(5, 2);
alert(result);

//^^ Result isnt defined
Because the variable is defined INSIDE of the function

// 2 ways to fix this

1. // decalre the variable OUTSIDE of the function

2. // decalre inside and add a 

return result; 

// Than add 

var(result) = (5, 2);

alert(result)



///Highlite info than hold ALT and uo and down arrows to move code...

D. R. Y
Dont repeate yourself 

