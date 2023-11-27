# Pomodoro-Application

## Overview

This Pomodoro Timer is a simple Python application built with Tkinter. It helps users manage work and break intervals efficiently using the Pomodoro Technique. The timer alternates between work sessions and breaks, providing a focused and productive workflow.

## Features

- **Work Sessions**: Set for 1 minute each.
- **Short Breaks**: 1 minute.
- **Long Breaks**: After every 8 work sessions, lasting 20 minutes.
- **Countdown Display**: Shows minutes and seconds remaining in the current interval.
- **Start and Reset Buttons**: Control the timer.
- **Check Marks**: Track completed work sessions with checkmarks.

## How to Use

1. Click the "Start" button to initiate the Pomodoro Timer.
2. The timer alternates between work sessions and breaks.
3. After 8 work sessions, a longer break is scheduled.
4. Click the "Reset" button to stop the timer and reset the session count.

## UI Setup

- The timer display is centered around a tomato image, representing the Pomodoro Technique.
- Start and reset buttons control the timer.
- Checkmarks indicate completed work sessions.

## Dependencies

- Python 3.x
- Tkinter (for GUI)

## How to Run

1. Clone the repository to your local machine.

```bash
git clone https://github.com/your-username/pomodoro-timer.git
cd pomodoro-timer
```

2. Run the application.
```bash
Copy code
python pomodoro_timer.py
```
## File Structure
- pomodoro_timer.py: The main Python script containing the Pomodoro Timer application.
- tomato.png: Tomato image used in the GUI.
