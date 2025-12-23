# Focus Companion | Lofi Study Buddy
A minimalist, aesthetically pleasing Pomodoro timer designed to enhance productivity through a "virtual pet" interaction and an integrated task management system. This application provides a focused environment for studying or working, featuring a clean, responsive UI inspired by lofi aesthetics.

## Key Features
Smart Pomodoro Timer: A pre-configured 25-minute focus timer with Start, Pause, and Reset functionality.

Dynamic Pet States: An interactive emoji "buddy" that reacts to your workflow:

Sleeping (😴): Idle/Reset state.

Focused (😎): Active studying state.

Thinking (🤔): Paused state.

Party (🥳): Session completed state.

Integrated To-Do List: A built-in task manager located directly below the timer to keep track of session goals.

Persistent Storage: Utilizes localStorage to ensure your task list remains saved even after refreshing the browser.

Audio Notifications: Plays a chime when the focus session is successfully completed.

Interactive UI: Supports click-to-complete (strike-through) for tasks and a bulk "Clear All" option.

## Technical Stack
HTML5: Semantic structure and layout.

CSS3: Custom variables, Flexbox for centering, and keyframe animations for the "floating" pet effect.

JavaScript (ES6+): Timer logic, DOM manipulation, and LocalStorage integration.

## How to Use
Set Your Goal: Type a task in the "Add a task..." input field and click Add.

Start Focusing: Click the Start button to begin the 25-minute countdown.

Manage Tasks: Click on any task in your list to cross it out once completed.

Complete & Reset: Once the timer hits zero, an alarm will sound. Click Reset to return to the sleeping state for your break.

## Installation
No installation is required. This is a portable, single-file web application.

Save the code as index.html.

Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
