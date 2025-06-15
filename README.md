🐍 Snake Game with Pygame
A classic Snake Game built using the Python pygame library. Eat apples, grow longer, avoid collisions—and see how high you can score!

🎮 Game Features
🍎 Apple generation and random movement

🐍 Snake movement in four directions

📈 Score tracking

💥 Collision detection with self and walls

🔊 Background music and sound effects

🖼️ Custom graphics for snake, apple, and background

🧰 Requirements
Python 3.x

Pygame library

Install Pygame via pip if you don't have it:

pip install pygame
🚀 How to Run
Make sure the following files are present in the same directory:

snakegame.py

block.jpg (snake image)

apple.jpg (apple image)

background.jpg (background image)

bg_music.mp3 (background music)

ding.mp3 (sound when apple is eaten)

crash.mp3 (sound when snake crashes)

Run the game:
`python snakegame.py`
Controls:

Arrow keys: Move the snake

Enter: Restart after game over

Esc: Exit the game

🛠️ Code Structure
Snake: Handles the snake's movement, growth, and rendering

Apple: Manages apple position and drawing

Game: Orchestrates game logic, collision detection, score display, and main loop

🔊 Audio & Graphics
Ensure the required media files are present and named exactly:

Audio: bg_music.mp3, ding.mp3, crash.mp3

Images: block.jpg, apple.jpg, background.jpg
