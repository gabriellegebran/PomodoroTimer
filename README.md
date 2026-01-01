# Pomodoro Timer (Tkinter)

A simple Pomodoro Timer desktop application built with Python and Tkinter. This app helps improve focus and productvity by alternating between work sessions and breaks using the Pomodoro Technique.

## Features
- 25-minute Pomodoro timer
- 5-minute short break
- 15-minute long break (after every 4 Pomodoros)
- Pomodoro counter
- Skip current timer
- Reset all timers
- Uses threading to prevent UI freezing
- Clean tab-based interface using ttk.Notebook

## Technologies Used
- Python 3
- Tkinter (GUI)
- ttk (styled widgets)
- threading
- time

## How It Works
- The app detects which tab is selected to determine the timer type
- When a Pomodoro finishes:
    - The Pomodoro counter increases
    - A long break starts every 4 Pomodoros, otherwise a short break starts
- Timers automatically chain into the next session
- Threading ensures the GUI stays responsive while the timer runs

## Future improvements
- Customizable timer lengths
- Sound notifications
- Pause/resume button

## Learning Purpose
This project was created to practice:
- Python GUI development
- Threading in desktop applications
- Event-driven programming
- Object-oriented design

## License
This project is open-sourced and free to use for learning purposes

