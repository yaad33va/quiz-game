# Quiz Game

## Overview

The Quiz Game is a simple web-based application that allows users to test their knowledge with fun and engaging questions. The game dynamically loads questions from a `.txt` file and visualizes them in an interactive user interface.

## Features

- **Dynamic Questions**: Questions are fetched from a `.txt` file, making it easy to update or add new questions.
- **Progress Tracking**: A progress bar shows the user's progress through the quiz.
- **Score Display**: The user's score is updated in real-time.
- **Results Screen**: Displays the user's final score and a motivational message based on their performance.
- **Responsive Design**: The game is optimized for both desktop and mobile devices.

## How to Run

1. Clone the repository or download the project files.
2. Open the `index.html` file in a web browser.
3. Click the "Start Quiz" button to begin.

## Adding Questions

To add new questions:

1. Open the `questions.txt` file.
2. Add a new line in the following format:
   ```
   Question?|Answer1,false|Answer2,false|Answer3,true|Answer4,false
   ```
   - Replace `Question?` with the actual question.
   - Replace `Answer1`, `Answer2`, etc., with the answer options.
   - Mark the correct answer with `true` and the incorrect ones with `false`.

## Technologies Used

- HTML
- CSS
- JavaScript
