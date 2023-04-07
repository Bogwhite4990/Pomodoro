# Pomodoro Timer

This is a simple Pomodoro Timer application built using Python and Tkinter GUI library. The Pomodoro Technique is a time management method developed by Francesco Cirillo in the late 1980s. The technique uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks.

## Features

Timer with work, short break, and long break intervals.
Start and Reset buttons to control the timer.
Checkmark display to keep track of completed work sessions.

## How to Use

1. Clone or download the repository to your local machine.
2. Make sure you have Python installed on your machine.
3. Install the Tkinter library if not already installed. You can install it using pip, the Python package manager, with the following command: pip install tk.
4. Run the pomodoro_timer.py file using Python.
5. The Pomodoro Timer window will open.
6. Click on the "Start" button to start the timer. The timer will start with a default work interval of 25 minutes.
7. When the work interval is over, the timer will automatically switch to a short break interval of 5 minutes. After that, it will switch to work interval again. This cycle will continue until 4 work intervals are completed.
8. After 4 work intervals, the timer will switch to a long break interval of 20 minutes.
9. You can reset the timer anytime during the intervals by clicking on the "Reset" button.
10. Completed work intervals will be marked with a checkmark display.

## Customization

You can customize the work, short break, and long break intervals by modifying the following constants in the code:

WORK_MIN: Work interval duration in minutes (default: 25).
SHORT_BREAK_MIN: Short break interval duration in minutes (default: 5).
LONG_BREAK_MIN: Long break interval duration in minutes (default: 20).
You can also customize the appearance of the timer window by modifying the following constants in the code:

PINK, RED, GREEN, YELLOW: Colors used for UI elements (default values are provided).
FONT_NAME: Font used for timer display (default: "Courier").

Enjoy using the Pomodoro Timer! Happy productivity!
