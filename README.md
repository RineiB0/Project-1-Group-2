# Project 1 Group 2
 This our first project attempt!
 Group 2: Mary, Ying, Renée 

hi both!

I'd like to share some basic thoughts on our  project to your references
(this is not even a draft, just some random thoughts)

I think we need the following files and materials:
- 1x HTML to start
- 1x CSS for modifying
- 1x JS for coding

Furthermore we need to save following gif-files in a folder 
- rock/paper/scissors/start/end/draw/win/lose/thanks

OK, so much for today

Now wish you all a nice holiday!


Hi, here a code draft to your references.


let you = "You";
let comp = "Computer";

if(you === "Sissors" && comp === "Paper"){
    console.log("You have sissors and computer has paper.");
    console.log("You win!");
} else if(comp === "Sissors" && you === "Paper"){
    console.log("You have paper and computer has sissors.");
    console.log("Computer wins!");
} else if(you === "Sissors" && comp === "Sissors" || you === "Paper" && comp === "Paper"){
    console.log("Both you and computer have " + you.);
    console.log("It's a tie!");
} else if(you === "Rock" && comp === "Sissors"){
    console.log("You have rock and computer has sissors.");
    console.log("You win!");
} else if(comp === "Rock" && you === "Sissors"){
    console.log("Computer has rock and you have sissors.");
    console.log("Computer wins!");
} else if(you === "Rock" && comp === "Rock" || you === "Sissors" && comp === "Sissors"){
    console.log("Both you and computer have " + you.);
    console.log("It's a tie!");
} else if(you === "Paper" && comp === "Rock"){
    console.log("You have paper and computer has rock.");
    console.log("You win!");
} else if(comp === "Paper" && you === "Rock"){
    console.log("Computer has paper and you have rock.");
    console.log("Computer wins!");
} else if(you === "Paper" && comp === "Paper" || you === "Rock" && comp === "Rock"){
    console.log("Both you and computer have " + you.);
    console.log("It's a tie!");
} 



