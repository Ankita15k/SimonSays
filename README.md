# Simon Says - Memory Visual Game

## 🎮 Game Overview

This project is a web-based implementation of the classic electronic memory game, **Simon Says**. The game is built to test and challenge your visual memory. Players must watch a sequence of colors light up and then repeat the sequence in the correct order. With each successful round, the sequence gets longer and more challenging. This version includes a "memory visual" feature, where the entire sequence is replayed for the player before they have to enter their guess, aiding in memory recall.

## ✨ Features

* **Classic Simon Gameplay:** Watch the pattern and repeat it.
* **Increasing Difficulty:** The sequence gets one step longer with every correct guess.
* **Visual Memory Aid:** The complete sequence is replayed for you before you start your turn.
* **High Score Tracking:** The game keeps track of the highest score achieved in the current session.
* **Responsive Design:** The game is playable on various screen sizes, from desktops to mobile phones.
* **Sound Effects:** Interactive sounds for each color press to provide audio feedback.
* **Start & Restart:** Easily start a new game at any point.

## 🕹️ How to Play

1.  **Start the Game:** Press any key to begin the game. The game will indicate "Level 1".
2.  **Watch the Sequence:** The game will light up one or more of the colored buttons in a specific sequence. Pay close attention!
3.  **Repeat the Sequence:** After the game has shown you the sequence, it's your turn. Click on the colored buttons in the exact same order.
4.  **Advance to the Next Level:** If you correctly repeat the sequence, you will advance to the next level, and the game will add a new color to the end of the sequence.
5.  **Game Over:** If you press the wrong color, the game will end. The screen will flash red, and your final score (the last level you completed) will be displayed.
6.  **Restart:** Press any key to start a new game from Level 1.

## 🛠️ Technologies Used

This project is built using fundamental web technologies:

* **HTML:** Structures the game's content and layout.
* **CSS:** Styles the game, including the colored buttons, layout, and animations.
* **JavaScript:** Implements all the game logic, including generating sequences, handling user input, and tracking the score.

## 🚀 Commands & Setup

To get the project running on your local machine, open your terminal or command prompt and follow these steps.

1.  **Clone the repository**
    * This command downloads the project files from GitHub to your computer. Replace `your-username/your-repo-name` with your actual GitHub username and repository name.
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```

2.  **Navigate to the project directory**
    * This command moves you into the folder you just created.
    ```bash
    cd your-repo-name
    ```

3.  **Open the game in your browser**
    * This command opens the `index.html` file in your default web browser.

    * **On macOS:**
        ```bash
        open index.html
        ```

    * **On Windows:**
        ```bash
        start index.html
        ```

    * **On Linux:**
        ```bash
        xdg-open index.html
        ```

That's it! The game will be up and running. Enjoy playing!
