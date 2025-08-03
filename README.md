ALX Simple Quiz - README
📘 Description
This is a basic interactive quiz application built with HTML, CSS, and JavaScript.
The quiz consists of a single question: “What is 2 + 2?”
The goal of this project is to demonstrate foundational JavaScript skills including event handling, DOM manipulation, and basic conditional logic.

📋 Features
Simple and clean user interface

One multiple-choice question

Immediate feedback upon submitting an answer

All logic handled on the client-side using JavaScript

🗂️ File Structure
bash
Copy code
ALX_Simple_Quiz/
├── index.html     # Contains the quiz question and structure
├── styles.css     # Provides styling for the quiz layout
└── quiz.js        # Implements quiz logic and validation
🚀 How to Use
Clone or download the repository named ALX_Simple_Quiz.

Open the index.html file in any modern web browser.

Select an answer to the quiz question.

Click the Submit Answer button.

View feedback below the button indicating whether your answer was correct.

🧠 JavaScript Logic
A function named checkAnswer is defined in quiz.js.

It checks which radio option is selected.

If the selected value equals "4" (the correct answer), the message "Correct! Well done." is displayed.

If not, the message "That's incorrect. Try again!" appears.

If no answer is selected, it prompts the user to choose one.