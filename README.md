<!DOCTYPE html>

<html>

<head>

<meta name="viewport" content="width=device-width, initial-scale=1">




<style>  

body {   

background-color: lavender

}   

h1 {   

font-size: 40px;   

color: black;  

text-align: center;   




<body>  

</body>   

</style>   

  


<style>

.accordion {

background-color: pink;

color: #444;

cursor: pointer;

padding: 18px;

width: 100%;

border: none;

text-align: left;

outline: none;

font-size: 15px;

transition: 0.4s;

}

.active, .accordion:hover {

background-color: violet;

}

.panel {

padding: 0 18px;

background-color: pink;

max-height: 0;

overflow: hidden;

transition: max-height 0.2s ease-out;

}

var acc = document.getElementsByClassName("accordion");

var i;

for (i = 0; i < acc.length; i++) {

acc[i].addEventListener("click", function() {

this.classList.toggle("active");

var panel = this.nextElementSibling;

if (panel.style.maxHeight) {

panel.style.maxHeight = null;

} else {

panel.style.maxHeight = panel.scrollHeight + "px";

}

});

}

</style>

</head>

<body>

<h2>Questions about "Rock Paper Scissor" </h2>

<p>Click to open the collapsible content.</p>

<button class="accordion">1.What is the game "Catch the falling object"?</button>

<div class="panel">

<p>The game is a digital version of Rock, Paper, Scissors. It uses the micro:bit to display one of the three options—Rock, Paper, or Scissors—after being shaken. It's a fun way to play the classic game using technology.</p>


</div>

<button class="accordion">2.How is it suitable for a 6–12-year-old? </button>

<div class="panel">

<p>It’s perfect for kids because:

It’s simple to play—just shake the micro:bit to get a result.
The interactive display makes it exciting.
It teaches randomness and basic coding concepts.
Kids can play against friends, making it a social activity.
It encourages creativity, as they can customize or improve the game.</p>

</div>

<button class="accordion">3.How does the game work? </button>

<div class="panel">
<p>Here’s how it works:

When you shake the micro:bit, the accelerometer detects the motion.
The program generates a random number (0, 1, or 2).
0 = Rock
1 = Paper
2 = Scissors
The micro:bit then displays the corresponding result on its LED screen.
You can compare results with a friend to see who wins using the game rules:
Rock beats Scissors.
Scissors beats Paper.
Paper beats Rock./p>

</div>
<button class="accordion">4.What would you change and why?</button>

<div class="panel">

<p>I would make the following changes to improve the game:

Add Sounds: To make it more engaging, play sounds when shaking or showing results.
Add Player Input: Let players choose their option using buttons, making it more interactive.
Score Tracking: Add a scoreboard to track wins and ties over multiple rounds.
Animations: Use animations on the LED screen for Rock, Paper, and Scissors.
Multiplayer Mode: Allow two players to select their choices on the same micro:bit.
<p><strong>Why:</strong> These changes make the game more exciting, interactive, and replayable for kids.</p>


</div>



<button class="accordion">5.Explain the code in your video. </button>

<div class="panel">

<p>Here’s how the code works:

on shake: The game starts when you shake the micro:bit.
set choice to pick random 0 to 2: This generates a random number to decide the result.
Conditionals (if, else if, else):
If the number is 0, the micro:bit displays "Rock."
If it’s 1, it displays "Paper."
Otherwise, it displays "Scissors."
Each time you shake, the program runs through these steps to display a new random result.

</p>



</div>


<button class="accordion">6.What did you learn?</button>

<div class="panel">

<p>I learned several things while working on this game:

How to use conditional logic (if-else statements) to make decisions in code.
How to generate random numbers for creating unpredictable outcomes.
How the micro:bit features like accelerometers and LED displays work.
How to design simple games that are fun and interactive.
The importance of debugging and problem-solving to fix errors in the code.</p>




</div>

<script>

var acc = document.getElementsByClassName("accordion");

var i;

for (i = 0; i < acc.length; i++) {

acc[i].addEventListener("click", function() {

this.classList.toggle("active");

var panel = this.nextElementSibling;

if (panel.style.maxHeight) {

panel.style.maxHeight = null;

this.setAttribute("aria-expanded", "false");

} else {

panel.style.maxHeight = panel.scrollHeight + "px";

this.setAttribute("aria-expanded", "true");

}

});

}

</script>

</body>

</html>



<style>   

.button {  

background-color: lavender;   

 border: none;   

color: white;   

padding: 15px 32px; 
text-align: center;  

 

text-decoration: none;  

 

display: inline-block;  

 

font-size: 16px;  

 

margin: 4px 2px;  

 

cursor: pointer;  

 

}  

 

 

 

