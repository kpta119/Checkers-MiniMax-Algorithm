# MiniMax with Alpha-Beta Pruning for Checkers

## Project Description
This project implements the **MiniMax algorithm with Alpha-Beta Pruning** for the game of checkers. The game is developed in **Python**, using **Pygame** for visualization and various evaluation functions.

## Technologies
- **Python**  
- **Pygame**  
- **NumPy**  
- **MiniMax algorithm with Alpha-Beta pruning**  

## Features
- Implementation of multiple evaluation functions:
  - **basic_ev_func** – basic evaluation based on the number of pieces.
  - **group_prize_ev_func** – rewards piece grouping.
  - **push_to_opp_half_ev_func** – encourages advancing pieces into the opponent's half.
  - **push_forward_ev_func** – favors aggressive forward movement.
- **Player vs AI** and **AI vs AI** game modes.
- Supports checkers rules, including capturing and king promotion.
