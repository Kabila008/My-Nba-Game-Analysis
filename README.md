# Welcome to My Nba Game Analysis
***

## Task
This project is an analysis tool for processing data from NBA basketball games. 
The main challenge is understanding and processing the various game events to 
calculate and display statistics for players and teams. Some of the specific challenges include:
•	Data Processing and Parsing: The code needs to read data from a CSV file containing 
    game events, and then parse and process these events correctly to extract relevant 
    information. These events are stored in a specific format with pipe-delimited fields, 
    making parsing complex.
•	Pattern Matching and Regular Expressions: The code uses regular expressions to extract 
    player names and relevant information from the event descriptions. Crafting the correct 
    regex patterns to match different event types can be challenging.
•	Data Aggregation and Calculation: After parsing, the code needs to aggregate and 
    calculate various statistics such as field goals, three-pointers, rebounds, etc. This involves 
    correctly associating players with their respective teams and tracking their performance 
    over the course of the game.
•	Display and Formatting: The code then formats and displays the calculated statistics in a 
    tabular format, which requires careful formatting to ensure alignment and readability.


## Description
The problem was solved by breaking it down into several functions that each handle a specific 
aspect of data processing and analysis.
•	The content function reads the game events from a file and stores them in a list of lists. 
•	The assemble function extracts team names and players' data from the events.
•	The directory function defines event patterns and corresponding actions. These 
    patterns are used to match events and update player statistics accordingly.
•	The transfer function iterates through events and updates player statistics based on 
    matched patterns. 
•	The analyse_nba_game function orchestrates the analysis process by 
    calling various functions to extract and calculate player and team statistics.
•	The evaluate_sum function calculates sum and percentage statistics for a given group 
    of players (either a team or the overall game).
•	The main_counter function is responsible for displaying the formatted results. It prints 
    individual player statistics and calculates and prints team totals for each team.


## Installation
Download a Python distribution like Anaconda or use the official Python installer from 
python.org. Install it, then choose an Integrated Development Environment (IDE) like Visual 
Studio Code or PyCharm. Download the IDE, install Python extension, and you're ready to code.

Use your system's package manager (e.g., apt for Ubuntu, brew for macOS) and run sudo apt 
install python3 or brew install python. Verify by typing python3 in the terminal. For Windows, 
download the installer from python.org, run it, and check "Add Python to PATH" during installation.

Open a terminal and use the command pip install python3 to install Python packages. 


## Usage
The code is written in Python. To use this project:
•	Make sure you have Python installed on your system.
•	Save the provided code in a .py file.
•	Place the game event data file ("nba_game_warriors_thunder_20181016.txt") in the 
    same directory as the code.
•	Run the code using a Python interpreter (e.g., python my_nba_game_analysis.py).
