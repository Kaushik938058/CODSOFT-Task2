Name:Kaushik

Company:CODSOFT

ID:BY25RY255105

Project Title: Tic-Tac-Toe AI Agent

Domain: Artificial Intelligence

OVERVIEW OF THE PROJECT
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Objective
The main goal of this project is to build an AI agent that plays the classic game of Tic-Tac-Toe against a human . The AI is designed to be unbeatable, meaning it will either win the game or force a draw, but never lose .

Technical Implementation
The project utilizes the Minimax algorithm, a recursive search algorithm used in decision theory and game theory .

Minimax Logic: The algorithm evaluates all possible future moves in the game tree. It assigns a value to each end state (+1 for AI win, -1 for Human win, 0 for Draw) and chooses the move that maximizes the AI's score while minimizing the human's potential score.

Game Theory: This implementation demonstrates the concept of a zero-sum game, where one player's advantage is the other's disadvantage .

Search Algorithms: It serves as a practical example of basic search algorithms navigating through a problem space .

Key Features
Unbeatable Strategy: The AI anticipates the human player's optimal moves and blocks them.

Interactive Gameplay: A command-line interface allows the user to input moves (0-8) and view the board state.

State Evaluation: The system automatically checks for wins, losses, or draws after every turn.

Technologies Used
Language: Python

Libraries: math (Standard library used for infinity values in the algorithm)

OUTPUT
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Python 3.12.2 (tags/v3.12.2:6abddd9, Feb  6 2024, 21:26:36) [MSC v.1937 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.

= RESTART: C:\internship\tictactoe.py
Welcome to Unbeatable Tic-Tac-Toe!
You are 'X'. AI is 'O'.


   |   |   
---|---|---
   |   |   
---|---|---
   |   |   


Enter position (1-9): 1
AI is thinking...


 X |   |   
---|---|---
   | O |   
---|---|---
   |   |   


Enter position (1-9): 2
AI is thinking...


 X | X | O 
---|---|---
   | O |   
---|---|---
   |   |   


Enter position (1-9): 7
AI is thinking...


 X | X | O 
---|---|---
 O | O |   
---|---|---
 X |   |   


Enter position (1-9): 6
AI is thinking...


 X | X | O 
---|---|---
 O | O | X 
---|---|---
 X | O |   


Enter position (1-9): 9


 X | X | O 
---|---|---
 O | O | X 
---|---|---
 X | O | X 


It's a Draw!

