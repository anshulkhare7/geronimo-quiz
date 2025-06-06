# Geronimo Stilton Progressive Quiz Adventure

Test your knowledge of the popular Geronimo Stilton book series with this fun, browser-based quiz game!

## Overview

This project is a **Geronimo Stilton Progressive Quiz Adventure**, designed for fans to test their familiarity with the exciting tales of Geronimo Stilton. Users can progressively unlock quizzes for different books, track their completion, and enjoy a variety of engaging quiz mechanics. The entire game is self-contained within a single HTML file (`index.html`), meaning all data and logic run directly in your browser. There is no server-side component.

## Features

*   **Multiple Book Quizzes:** Offers quizzes for a series of Geronimo Stilton books (currently 10).
*   **Progressive Unlocking:** Quizzes must be completed with a perfect score to unlock the next book's quiz, encouraging mastery.
*   **Detailed Scoring System:** Scores are calculated with +1 point for correctly answered questions, -0.5 points for incorrect answers, and -0.25 points for questions left unattempted if the timer runs out.
*   **Timed Quizzes:** Each quiz has a 5-minute timer to challenge the player.
*   **Cheat Codes:** Players can unlock and use cheat codes to bypass levels they have already mastered.
*   **Dark Mode:** A toggle switch allows users to switch between light and dark themes for comfortable viewing.
*   **Responsive Design:** The application is designed to work seamlessly on both desktop and mobile devices.
*   **Browser-Based Progress:** User progress (completed and unlocked levels) is saved locally in the browser using localStorage.
*   **Quiz Instructions:** Each quiz is preceded by an instructions page outlining the rules, time limit, and scoring.
*   **Comprehensive Results:** After each quiz, a results page displays the score, a detailed breakdown (correct, incorrect, unattempted), and tailored feedback.
*   **Retry Option:** Users can retry quizzes to improve their scores or achieve perfection.

## How to Play

Welcome to the Geronimo Stilton Progressive Quiz Adventure! Here’s how to get started and navigate the game:

1.  **Starting the Game:**
    *   When you open the page, you'll land on the **Home Page**.
    *   Here, you'll see a welcome message, a summary of your overall quiz progress, and a list of Geronimo Stilton books.

2.  **Selecting a Book Quiz:**
    *   Browse the list of available books. Each book has its own quiz.
    *   **Unlocked Books:** Click "Play" (or "Play Again" if you've completed it before) to start a quiz for an unlocked book.
    *   **Locked Books:** Most books will initially be locked. To unlock a book's quiz, you must first achieve a **perfect score** on the quiz for the preceding book.
    *   Alternatively, if a book is locked, you can click "Unlock". This will prompt you to enter a **cheat code** if you know it (cheat codes are revealed when you get a perfect score on a quiz).

3.  **Quiz Instructions:**
    *   After selecting a book, you'll see an **Instructions Page**.
    *   This page provides details about the quiz, including the time limit (5 minutes), scoring rules, and that some questions might have multiple correct answers.
    *   Click "Start Quiz" when you're ready.

4.  **Taking the Quiz:**
    *   Questions are multiple-choice. Select the answer(s) you think are correct by checking the box(es).
    *   **Multiple Correct Answers:** Pay attention, as some questions may require you to select more than one option to be fully correct.
    *   **Timer:** A 5-minute timer will start as soon as the quiz begins. Keep an eye on it!
    *   **Auto-Submission:** If the timer runs out before you submit, your answers will be submitted automatically.

5.  **Submitting and Results:**
    *   Once you've answered all questions, click "Submit Answers".
    *   You'll be taken to the **Results Page**, which shows:
        *   Your score and a percentage.
        *   A breakdown of correct, incorrect, and unattempted questions.
        *   Feedback on your performance.
        *   If you achieve a **perfect score**, the cheat code for that book's quiz will be revealed! Make sure to note it down if you want to skip this quiz in the future.
    *   From the results page, you can choose to "Try Again" or, if you've unlocked it, proceed to the "Next Book".

6.  **Progress and Unlocking:**
    *   Your progress (completed books, unlocked books) is automatically saved in your browser.
    *   Achieving a perfect score on a book's quiz automatically unlocks the quiz for the next book in the series.

7.  **Using Cheat Codes:**
    *   If you click "Unlock" on a locked book, a pop-up will appear.
    *   Enter the cheat code for that specific book to unlock and mark it as completed, which will also unlock the subsequent book.

8.  **Additional Features:**
    *   **Dark Mode:** Use the toggle switch (usually 🌓 icon) at the top-left to switch between light and dark themes.
    *   **Home Button:** During a quiz or on an instructions page, click the "Home" button (usually at the bottom-right) to return to the main book selection screen.

Have a fabumouse time testing your Geronimo Stilton knowledge!

## Book Series Included

The quiz currently includes questions from the following Geronimo Stilton books:

1.  Lost Treasure of the Emerald Eye
2.  The Curse of the Cheese Pyramid
3.  Cat and Mouse in a Haunted House
4.  I'm Too Fond of My Fur
5.  Four Mice Deep in the Jungle
6.  Paws Off, Cheddarface!
7.  Red Pizzas for a Blue Count
8.  Attack of the Bandit Cats
9.  A Fabumouse Vacation for Geronimo
10. All Because of a Cup of Coffee

## Technical Details

This quiz adventure is built with simplicity and accessibility in mind, relying on fundamental web technologies:

*   **Single-File Architecture:** The entire application—HTML structure, CSS styling, and JavaScript logic—is contained within a single `index.html` file.
*   **Vanilla JavaScript:** All interactive elements, quiz logic, progress tracking, and DOM manipulation are handled using plain (vanilla) JavaScript, without reliance on any external JavaScript frameworks or libraries.
*   **CSS Styling:** The visual presentation, including layout, responsiveness, and the dark mode feature, is achieved using standard CSS. CSS variables are utilized for theme management (e.g., colors for light and dark modes).
*   **Local Storage for Progress:** User game progress, such as completed quizzes and unlocked levels, is saved directly in the user's web browser via the `localStorage` API. This allows progress to persist between sessions on the same browser.
*   **Client-Side Only:** The application runs entirely on the client-side (in the user's browser). There are no server-side components, databases, or backend processing involved.

## Acknowledgements

- This project was largely developed with the assistance of AI. The development conversations can be found here:
    - [Part 1](https://claude.ai/share/4efff8c1-a893-44b6-8df1-62ed9447a85c)
    - [Part 2](https://claude.ai/share/54f93456-acba-4d79-8ac1-5a18d80fad7f)
- Hosted on [Surge.sh](https://surge.sh/). The live quiz can be accessed [here](https://gero.surge.sh/).
