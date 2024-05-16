# Pomodoro Timer

A simple Pomodoro Timer application built using Python and Tkinter. The Pomodoro Technique is a time management method that uses a timer to break down work into intervals, traditionally 25 minutes in length, separated by short breaks.

## Features

- **Work Sessions**: 25-minute work intervals.
- **Short Breaks**: 5-minute breaks after each work session.
- **Long Breaks**: 20-minute break after every four work sessions.
- **Visual Timer**: Countdown display with a tomato image.
- **Session Tracking**: Check marks to track the number of completed work sessions.

## Screenshot

<img width="528" alt="image" src="https://github.com/EgemenErin/pomodoro-app/assets/113554575/3e5680dd-0f6a-4479-a2c8-426a499439eb">


## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/pomodoro-timer.git
    cd pomodoro-timer
    ```

2. **Install dependencies**:
    - This project requires Python 3 and Tkinter. Tkinter usually comes pre-installed with Python, but if not, you can install it using:
    ```bash
    sudo apt-get install python3-tk
    ```
    
3. **Run the application**:
    ```bash
    python pomodoro.py
    ```

## Usage

1. **Start the Timer**: Click the `Start` button to begin the first work session.
2. **Reset the Timer**: Click the `Reset` button to stop the current timer and reset the session counter.

## Code Overview

The main components of the application are:

- **Constants**: Define colors, font, and session durations.
- **Functions**:
  - `reset_timer()`: Resets the timer and session counter.
  - `zaman()`: Manages the timer mechanism, switching between work and break periods.
  - `count_down()`: Handles the countdown logic and updates the UI accordingly.
- **UI Setup**: Initializes the main application window, labels, buttons, and canvas.

## Files

- `pomodoro.py`: The main script containing the application logic.
- `tomato.png`: Image file used for the timer background.
- `screenshot.png`: Screenshot of the application (to be added for the README).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

Happy time managing!
