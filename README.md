# my-python-weekly-tasks
A weekly repository for my python programming tasks featuring algorithm designs, AI simulation and data visualization.
Week 2 Assignment Directory 1. 
Task 1: Simple AI Agent Tic-Tac-Toe Simulation: Simple AI Agent Tic-Tac-Toe Simulation A Python implementation of a turn-based Tic-Tac-Toe game featuring an interactive simulation where a human player competes against a simple learning AI agent. 
Core Program Architecture: The program is structured directly around foundational game loops and agent heuristics:Define the Game Board: Configures and prints the 3x3 grid system dynamically tracking empty spaces and player markers; Check If a Player Has Won; Evaluates rows, columns, and diagonals after every move to confirm a winning state; Check If the Game is a Tie; Verifies if all 9 spaces are filled with no winning vectors met, terminating the game cleanly.
Main Game Loop: Orchestrates the primary game state, processing inputs from the human (Player O) and choices from the simple AI agent (Player X). Call the Main Game Loop:Instantiates and fires the script execution environment to initiate gameplay immediately upon launch.
Core Objectives: AI Agent Exploration:Provides exposure to rule-based heuristics and automated state detection, showing how an artificial agent can evaluate a board to make legal, competitive decisions. 
Functional Architecture: Breaking the assignment into clear modules reinforces clean, scalable software design.
 [Task 2: Monthly Sales and Profit Visualization]: Monthly Sales and Profit Visualization A Python data analysis project utilizing Pandas and Matplotlib to explore and visualize corporate sales performance metrics over a 12-month period.
Core Implementation
1.Data Localisation & Processing:Formatted a 12-month transaction dataset containing monthly product quantities and overall corporate profits. Transformed raw data into structured multidimensional arrays using a Pandas DataFrame.
2.Data Visualization:Exercise 1 (Line Plot):Plotted a continuous time-series line chart tracking `total_profit` across all months to monitor macro financial trends. 
Exercise 2 (Subplots): Designed a vertically stacked 2x1 grid layout. The top plot isolates units sold for `bathingsoap`, while the bottom plot maps `total_profit`, allowing for a direct comparison of a specific product's performance against overall revenue. 
Data Insights Extracted: End of Month Spikes & Mid-Month Decline:From the generated graphs, we extracted a crucial trend showing that units sold increase significantly at the end of the months and experience a slight decline toward the middle of the period. This exact pattern is mirrored perfectly by the profit trends. 
Correlation Analysis: Stacking charts as subplots using a shared X-axis makes it easy to see if a surge in bathing soap sales directly caused the company's total profit to go up.
Bypassing Network Restrictions:Hardcoding the verified dataset locally demonstrated an adaptable engineering work around when corporate or academic firewalls block external data links.
Technologies Used: Python 3,Jupyter Notebook (Development Environment),Pandas (Data Manipulation),Matplotlib.pyplot(Data Visualization)
