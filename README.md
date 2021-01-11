# Project Name
> Pig

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Coding Examples](#code-examples)
* [Features](#features)
* [Status](#status)
* [Contact](#contact)

## General info
The classic dice game, Pig! If you roll two sixes in a row, your entire score is reset! This was something I created during an online course on Udemy. CSS and HTML was provided by the instructor.

## Technologies
* HTML
* CSS
* JavaScript

## Code Examples
A small section of the JS in this project:
```
if (dice1 === 6 || dice2 === 6 && lastDice === 6) {
            //Player loses score
            scores[activePlayer] = 0;
            document.querySelector('#score-' + activePlayer).textContent = '0';
            nextPlayer();
        } 
````
    

## Features

* A nice, simple interface



To-do list:
* Redo site so it is mobile friendly. I would eventually like to turn this into an app you can play with friends.

## Status
Project is: In progress due to potential improvements


## Contact
Amy Scott
