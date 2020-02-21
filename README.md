# Project1
GA Class - Project 1 - Hangman

Details:
•	Goal - Create a working game application that allows one person to play Hangman.
•	Game Layout – An online screen with blank fields for each letter of a word displayed and field for a player to enter a guess at a letter. Also show the player how many guesses they have to solve the word. If a player solves the word, have a “Congratulations” and if they don’t solve it within the number of guesses allowed show that they “Failed”.

User Stories:
•	As a developer, I want to create a working hangman game so that one person can play the game.
•	As a player, I want to be able to pick a letter to try and solve the word of the game.
•	As a player, I want to know when I win or lose the game so I know when the game is over.
•	As a player, I want to know if I choose a correct letter so I can keep moving through the game.
•	As a player, I want to know if I got the letter wrong, so I can keep moving through the game.
•	As a player, I want to be able to see how many guesses I have remaining in the game so I can keep up with the game.

First Steps:
•	Create an HTML (index.html) document
•	Create a CSS (style.css) document
•	Create a JavaScript (main.js) document 
•	Add all documents to a new repository in my personal Git Hub
•	Design game board in CSS
•	Add elements in HTML for title/header and other verbiage on the board
•	Write pseudocode and determine logic of the game 
•	Add functionality using JavaScript
•	Test all details along the way.

Pseudocode:
•	Present board with the following:
  o	Header with title and message
  o	Simple instructions
  o	One word (Fireworks) with individual fields for each letter
  o	Make the letters hidden to start the game
  o	Give the player 5 lives to use for guesses
•	Game functionality:
  o	Create a function to allow a player to guess a letter.
  o	Player Guesses Letter
    	Store the letter in the “Guessed Letters” Array
      •	If letter guessed is in the game word (hidden)
        o	Uncover the letter(s) on the game board and allow player to pick another letter
      •	Else if, 
        o	The player guesses a letter that is not in the game word
          	Display the following phrase: “Sorry, you guessed a wrong letter. Try Again!”
          	Subtract a life from Remaining Lives
      •	Else If,
        o	The player guesses a letter that is already in the “Guessed Letters” Array,
          	Display the phrase “You already guessed that letter” 
          	Subtract a life from Remaining Lives


Game Levels
  •	Bronze:
    o	Create a game with one word and allow user to guess letters to identify the word
    o	The player will continue to guess letters until they have either solved the word or exhausted 5 chances(lives).
    o	If the player solves the correct word, they get a positive message
    o	If the player gets 5 incorrect guesses at letters, the game is over and they get a negative message
    o	Allow the game to be rest and be played again
  •	Silver:
    o	Create the Bronze version and add the following:
      	Add ability for player to input name
      	Add ability for the game to generate a random word from a predetermined array of words
      	Add some graphics that show body pieces on a hangman setup when incorrect guesses are made
  •	Gold:
    o Create the Silver version and add the following:
      	Add functionality to game that allows someone to choose the word to guess
      	Add a second player option
      	Keep score of each player
      	Maintain scoring history and number of games won for each player
      	Add more graphics when players get correct letters, incorrect letters and win or lose the game.

