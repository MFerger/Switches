A switch helps if you dont want to do consecutive else if statements.

var someVariable = //prompt a question or something here
switch(condition) { 
    case 'abc':
        // Thing to do
        break;
    case 'def':
        // Another thing
        break;
    case 'ghi':
        // Yet another thing
        break;
    default:
        // Default thing
        break;
}
-------------------------------------------------------------------------------------------------------------------------
example
var input = prompt("What color shirt are you wearing? Type your answer into here if you'd like to.");
switch(input) {
    case 'blue':
        console.log("You typed the correct answer");
        break;
    case 'green':
        console.log("Who wears green nowadays? Cmon now.");
        break;
    case 'red':
        console.log("That's nice. I don't care really.");
        break;
    default:
        console.log("Blue is the best. No other answer is accepted.");
        break;
}
