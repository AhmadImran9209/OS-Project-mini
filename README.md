# Bash Puzzle Game

This is a simple bash script that allows you to play a puzzle game. The goal of the game is to rearrange an array of numbers to match a predefined goal array using the 'u' (up), 'd' (down), 'r' (right), and 'l' (left) moves. The puzzle is initiated with a randomly shuffled array, and the script checks if the puzzle is solvable based on the number of inversions.

## How to Play

1. Run the script in a Bash environment.
2. The script will display the initial state of the puzzle array.
3. It will also show the goal state that you need to achieve.
4. You can make moves by entering 'u' (up), 'd' (down), 'r' (right), or 'l' (left).
5. The script will display the updated puzzle array after each move.
6. Continue making moves until you reach the goal array or decide to end the program by entering '0'.

## Puzzle Solvability

The script checks whether the initial puzzle state is solvable or not. The solvability is determined based on the parity of the number of inversions in the initial state and the goal state.

## Minimum Swaps

The script calculates the minimum number of swaps required to reach the goal array from the initial state.

## Legal Moves

The script provides information about legal moves at each step, preventing invalid moves.

## How to Run

1. Make the script executable:
    ```bash
    chmod +x puzzle_game.sh
    ```

2. Run the script:
    ```bash
    ./puzzle_game.sh
    ```

## Example Gameplay

```bash
Initial stage of Array:
1 2 3 4 0 
5 6 7 8 9 
10 11 12 13 14 
15 16 17 18 19 
20 21 22 23 24 

Goal stage of Array:
1 2 3 4 0 
5 6 7 8 9 
10 11 12 13 14 
15 16 17 18 19 
20 21 22 23 24 

Solvable
Minimum swaps for reached goal array: 0

Enter u for Up    Move
Enter d for Down  Move
Enter r for Right Move
Enter l for Left  Move
Enter 0 for end the program:
Legal moves are: u l r
