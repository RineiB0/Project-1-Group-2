# Project 1 Group 2
 This our first project attempt!
 Group 2: Mary, Ying, Renée 

hi both!

I'd like to share some basic thoughts on our  project to humanr references
(this is not even a draft, just some random thoughts)

I think we need the following files and materials:
- 1x HTML to start
- 1x CSS for modifying
- 1x JS for coding

Furthermore we need to save following gif-files in a folder 
- rock/paper/scissors/start/end/draw/win/lose/thanks

OK, so much for today

Now wish human all a nice holiday!


Hi, here a code draft to humanr references.


let human = "You";
let comp = "Computer";

if(human === "Sissors" && comp === "Paper"){
    console.log("human have sissors and computer has paper.");
    console.log("human win!");
} else if(comp === "Sissors" && human === "Paper"){
    console.log("human have paper and computer has sissors.");
    console.log("Computer wins!");
} else if(human === "Sissors" && comp === "Sissors" || human === "Paper" && comp === "Paper"){
    console.log("Both human and computer have " + human);
    console.log("It's a tie!");
} else if(human === "Rock" && comp === "Sissors"){
    console.log("human have rock and computer has sissors.");
    console.log("human win!");
} else if(comp === "Rock" && human === "Sissors"){
    console.log("Computer has rock and human have sissors.");
    console.log("Computer wins!");
} else if(human === "Rock" && comp === "Rock" || human === "Sissors" && comp === "Sissors"){
    console.log("Both human and computer have " + human);
    console.log("It's a tie!");
} else if(human === "Paper" && comp === "Rock"){
    console.log("human have paper and computer has rock.");
    console.log("human win!");
} else if(comp === "Paper" && human === "Rock"){
    console.log("Computer has paper and human have rock.");
    console.log("Computer wins!");
} else if(human === "Paper" && comp === "Paper" || human === "Rock" && comp === "Rock"){
    console.log("Both human and computer have " + human);
    console.log("It's a tie!");
} 



