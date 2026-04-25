# mini-arcade-game-suite
 Mini Arcade Game Suite
 Project Overview

The Mini Arcade Game Suite is a Python-based console application that integrates multiple simple games into a single interactive platform.
The project was developed progressively over 12 weeks, demonstrating the evolution from a basic program to a modular, feature-rich system.

It showcases core programming concepts such as:

- Modular Programming
- Object-Oriented Programming (OOP)
- File Handling
- Data Analysis & Visualization
 Objectives

- Develop a menu-driven mini arcade system
- Implement multiple games in one application
- Maintain player profiles and scores
- Provide analytics and graphical insights
- Demonstrate real-world Python development practices

 Features
 Games Included

- 🔢 Number Guessing Game
- 🔤 Hangman Game
 Player System

- Username-based login
- Tracks:
  - Games played
  - Total score
  - Average score
 Data Storage

- Player data stored using CSV files
- Persistent profiles (load & save)
  
 Analytics
- Performance statistics using Pandas
- Leaderboard generation
- 
 Visualization
- Graphical representation using Matplotlib
  - Bar chart (Leaderboard)
  - Pie chart (Game distribution)

 Project Structure

mini_arcade/
│
├── main.py            # Main program (menu & integration)
├── games.py           # Game logic (Guessing & Hangman)
├── player.py          # Player class (OOP)
├── storage.py         # Save & load player data
├── utils.py           # Input validation
├── analytics.py       # Data analysis (Pandas)
├── visual.py          # Graphs (Matplotlib)
│
├── data/
│   └── players.csv    # Stored player data
│
└── tests/
└── test_guessing.py  # Basic testing

Technologies Used

- Python 3.x
- Pandas (Data analysis)
- Matplotlib (Visualization)
- CSV File Handling

 How to Run the Project

1. Install Python (3.x)
2. Install required libraries:
   pip install pandas matplotlib
3. Open project in PyCharm
4. Run:
   main.py

 Functional Flow

1. User enters username
2. Profile is loaded or created
3. Menu options displayed:
   - Play Guessing Game
   - Play Hangman
   - View Stats
   - View Analytics
   - View Charts
   - Save & Exit
4. Scores are updated and stored

 Weekly Development Progress

Week| Description
Week 1| Basic Guessing Game
Week 2| Menu-driven program
Week 3| Added Hangman
Week 4| Modular structure
Week 5| Player class (OOP)
Week 6| Player integration
Week 7| Data storage (JSON/CSV)
Week 8| Input validation
Week 9| Data analytics (Pandas)
Week 10| Enhanced analysis
Week 11| Visualization (Matplotlib)
Week 12| Testing & error handling

Advantages

- Simple and user-friendly interface
- Modular and reusable code
- Demonstrates multiple Python concepts
- Persistent data storage
- Includes analytics and visualization

 Limitations

- Console-based (no GUI)
- Limited number of games
- No multiplayer functionality

 Future Enhancements

- GUI using Tkinter / Pygame
- More games (Snake, Tic-Tac-Toe)
- Online multiplayer support
- Cloud database integration
- AI-based gameplay

This project fulfills the requirements of:
- Project-Based Laboratory (Python Programming)
- Demonstrates modular development
- Includes analytics & visualization
- Suitable for viva demonstration in PyCharm
 Developed By
- Mohan

The Mini Arcade Game Suite successfully demonstrates the transformation of a simple Python program into a structured and scalable application. It highlights the importance of modular design, data handling, and visualization in real-world software development.
