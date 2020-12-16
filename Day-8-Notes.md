# *Day-8-Note*
[Go Home](/README.md)




Loops 


For loops

for (var i = 0; i < 10; i++){document.write(i);}

for // Keyword

var 1 = 0; // i variable intiially starts at 0 ; // assignment 

i < 10;    // if i is less than 10 than you should keep going ; // condition 

i++     // i +++ is a increment operator //

Document.write(i); //writing it into the HTML



for (var i = 0; i < 10; i++) {
    //Body of for loop
    console.log(i)   // THat puts it in the console. document.write(i) would put it in the html
}
//(While Loop)//
function ValidateUserPassword() {
    var storedPassword = "supersecretpassword";
    // While the user gives and INVALID password
    // Kepp prompting for a password
        var passwd; // variable that will hold user input 
        //while loop
        while(passwd !== storedPassword){

        }

// either or DO WHILE  or WHILE LOOP
        do {
            //body

        }while(passwd !== storedpassword);
    // Provide a prompt to user
            
        // Gave a prompt and stored it in a variable! // 
    // store their response in a variable
        if(passwd === storedPassword){} // dont need this


    // compare what they have inserted to my variable

}

// First step is to validate password. If its incorrect they are stuck above...
// if they are correct than they move on in the script. 
//// todo validate user password.
validateUserPassword();
