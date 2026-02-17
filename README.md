🐍 Snake Game – Java Swing

A classic Snake Game built using Java Swing and AWT. This desktop application recreates the traditional snake game where the player controls a snake to eat apples, grow longer, and avoid collisions.

🎮 Game Features

Smooth snake movement using arrow keys

Random apple generation

Score tracking system

Game Over screen with final score

Restart option (Press R to replay)

Collision detection (wall & self-collision)

Real-time game loop using Timer

🛠️ Technologies Used

Java

Java Swing (GUI)

AWT (Graphics & Event Handling)

OOP Concepts

🎯 Controls
Key	Action
⬅️ Left Arrow	Move Left
➡️ Right Arrow	Move Right
⬆️ Up Arrow	Move Up
⬇️ Down Arrow	Move Down
R	Restart Game
⚙️ How the Game Works

The snake moves continuously in the selected direction.

When the snake eats an apple:

The snake grows longer.

The score increases.

The game ends if:

The snake hits the wall.

The snake collides with itself.

After Game Over, press R to restart.

🚀 How to Run

Open the project in any Java IDE (NetBeans / IntelliJ / Eclipse).

Compile the project.

Run the main class that loads the GamePanel.

Start playing!

📂 Project Structure

GamePanel.java → Core game logic and rendering

Uses Timer for game loop handling

Inner KeyAdapter class for keyboard controls

📌 Future Improvements (Optional Enhancements)

Add difficulty levels

Add sound effects

Add high score saving

Add start menu screen

Add pause functionality

This project demonstrates:

Event-driven programming

Game loop implementation

Collision detection logic

Graphics rendering using Swing
