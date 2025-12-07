# Guess-the-Number
A simple CLI game where you must guess a secret number between 1 and 100 in 5 attempts.

## 🎮 How to Play
- The computer randomly selects a number from **1 to 100**  
- You have **5 attempts** to guess it correctly  
- After each guess, the game tells you whether the secret number (`secretNumber`) is **higher** or **lower**
  - If `|secretNumber - guess| >= 25`, it will show **'Freddo'**  
  - If `10 <= |secretNumber - guess| < 25`, it will show **'Caldo'**  
  - If `5 <= |secretNumber - guess| < 10`, it will show **'Brucia'**  
  - If `0 < |secretNumber - guess| < 5`, it will show **'Molto vicino!'**  
- If you guess the number in time, you win  
- If you run out of attempts, the game ends and the secret number is revealed!

## Build & Run
The game is already builded so you can just run it by starting the `.exe` or compiling the `.c`.

## License & credits
You can do what you want with this code.
