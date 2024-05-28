
Introduction

Hello friends, welcome to this new blog post. Today we have created a wonderful game which has been created with the help of HTML CSS and JavaScript. Friends, today we have created a game of rock paper which you must have played many times in mobile. Friends, we have created this project targeting those people who have less knowledge of JavaScript and are still learning JavaScript. Friends, if you want to increase your JavaScript skills, then you must see this project once. This project is very easy and good

Friends, we have used onclick function in the button in the HTML of this project so that if a user clicks on it then this button should actually work and friends, this button is not a normal button, we have used some icons on it which you can do it too

<div class=”weapons”>
<button onclick=”checker(‘rock’)”>
<i class=”far fa-hand-rock”></i>
</button>
<button onclick=”checker(‘paper’)”>
<i class=”far fa-hand-paper”></i>
</button>
<button onclick=”checker(‘scissor’)”>
<i class=”far fa-hand-scissors”></i>
</button>
</div>

Friends, I have designed this game very well. If you guys get out while playing the game, then you can also check your score. Friends, we have made this so that the user can get a good facility along with a good design. Yes, we have added all the features in this game which are there in a normal game.
Steps to Create Rock Paper Scissor Game:-

Friends, we have used HTML CSS and JavaScript to make this game and friends, if you use this project to increase your knowledge of JavaScript, then you will get very good knowledge of HTML CSS as well as JavaScript.

function checker(input){
var choices = [“rock”, “paper”, “scissor”];
var num = Math.floor(Math.random()*3);

document.getElementById(“comp_choice”).innerHTML =
` Computer choose <span> ${choices[num].toUpperCase()} </span>`;

document.getElementById(“user_choice”).innerHTML =
` You choose <span> ${input.toUpperCase()} </span>`;

Friends, we have used a computer in this game, that is, we have created a boat with which if you play the game, then the game will be played automatically through the boat in front of you. If you people select anything, then the game will be played in front of you. The bot will automatically make its proposal in the game, which makes playing the game a lot of fun. Friends, now to use the code of this game, you have to follow the steps given below.

    First of all you have to create a new folder in your computer, then you have to open that folder in your code editor.
    After opening the folder in the code editor, you have to create three files in this folder.
    index.html , style.css , script.js
    The structure of the Rock Paper game will be prepared in index.html, which will be in HTML, the code of which you will find below in the name of index.html heading, which you have to upload in your file, then a structure of your game will be ready.
    Now you will have to design the game, if you do not design the game properly then your game does not look good. To design the game, you will get the code named style.css below and upload it in your file. You have to do this then your game design will be ready.
    To make the game work properly, you will need JavaScript code, which you will find below, you have to upload that code in your file.

