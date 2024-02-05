# Time Counter Application

This Python script creates a simple Tkinter-based GUI for a time counter. Users can input hours, minutes, and seconds, and upon clicking the "Set Time Countdown" button, a countdown timer will start. When the time reaches zero, a messagebox will appear with the message "Time's up."

## Requirements
- Python 3
- Tkinter (standard GUI toolkit for Python)

## How to Use
1. Run the script.
2. Enter the desired hours, minutes, and seconds in the respective entry fields.
3. Click the "Set Time Countdown" button to start the countdown.
4. The GUI will display the countdown in real-time, and when the time reaches zero, a messagebox will appear.

## Code Overview
- The script uses Tkinter for GUI elements.
- Three Entry widgets allow users to input hours, minutes, and seconds.
- The `submit` function calculates the total time in seconds and initiates the countdown.
- The countdown is displayed in the Entry widgets in real-time.
- A `messagebox` is triggered when the countdown reaches zero.

## Note
- Ensure you have the required dependencies installed (`tkinter` is usually included with Python).

