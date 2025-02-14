# project_tictactoe
Repo created for The Odin Project intermediate JavaScript project: https://www.theodinproject.com/lessons/node-path-javascript-tic-tac-toe

Rules:
    1. Ensure that functions are factory functions wherever possible and are encapsulated
    2. Use no global variables if possible.

Pseudocode:
    1. Create a factory for drawing the game board
        1. gameBoard container using grid, rows using flexbox for viewport scaling
        2. boardGrid are elements that get drawn using a JavaScript loop
        3. Event listeners on each element. Check which player turn is currently active. onclick() have the current player's X or O displayed
        4. Set up a re-draw on reset button press.
    2. Write factory for game logic
        1. (need to determine best practice for keeping track of what markers have been placed)
        2. write logic that has a square check if the square next to it is the same type. If that square has another square next to it of the same type, player wins the game(? would need to figure out a way to check if it's the same type in the same direction, since a 3 grid L shape would trigger an erroneous win)
