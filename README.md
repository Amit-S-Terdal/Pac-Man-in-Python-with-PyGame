
# 🕹️ Pac-Man in Python with PyGame !

Welcome to **Pac-Man** built from scratch in Python using the PyGame library! This project is a modern recreation of the classic arcade game where players navigate Pac-Man through a maze, avoiding ghosts, and collecting all the pellets to advance to the next level. 🎮

## 🧠 Key Features
- **Classic Gameplay**: Navigate through a maze, eat all pellets while avoiding ghosts.
- **Ghost AI**: Each ghost has its unique movement pattern, making the game unpredictable.
- **Power-ups**: Eat the power pellet and turn the tables! Ghosts become vulnerable, and you can eat them.
- **Lives and Score**: Track your score and try to stay alive with the 3 initial lives.
- **Winning & Losing Conditions**: Lose all lives to the ghosts, or eat all pellets to win the game.

## 🚀 Getting Started
To get the game up and running, follow these steps:

### Prerequisites
- Python 3.x
- PyGame library

### Installation
1. **Clone this repository:**
   ```bash
   git clone https://github.com/amitterdal2906/pacman-python.git
   cd pacman-python
   ```
2. **Install the PyGame library:**
   ```bash
   pip install pygame
   ```

3. **Run the game:**
   ```bash
   python pacman.py
   ```

## 🎮 How to Play
- Use the arrow keys to move Pac-Man around the maze.
- Collect all the pellets while avoiding the ghosts.
- Eating a power pellet allows you to chase and eat ghosts for extra points.
- The game ends when you either run out of lives or clear the maze of all pellets.

## 🖼️ Game Preview
![Screenshot (143)](https://github.com/user-attachments/assets/3607c3be-639a-4119-beb0-1387aa2c28ff)
![Screenshot (144)](https://github.com/user-attachments/assets/4820a9c4-3942-4519-b062-76e24da0674a)
![Screenshot (146)](https://github.com/user-attachments/assets/79abd25d-4468-49f4-b95c-04de89eb4551)



## 💻 Code Structure
The project is divided into key modules for simplicity and scalability:

- **pacman.py**: Contains the main game loop and logic.
![Screenshot (142)](https://github.com/user-attachments/assets/631509d7-dab5-4dd9-9838-6e4e715433fd)

- **board.py**: Handles the structure of the maze.
![Screenshot (147)](https://github.com/user-attachments/assets/23dd30c0-408a-4c55-8d1c-b2f07f098f30)

- **assets/**: Contains images and sound effects for the game.
![Screenshot (169)](https://github.com/user-attachments/assets/50db554c-66e5-42e7-b36b-5bae884175eb)


## 🤖 Ghost AI
Each ghost has unique movement mechanics to give players a challenge:
- **Blinky**: The red ghost who directly chases Pac-Man.
- **Pinky**: The pink ghost tries to position itself in front of Pac-Man.
- **Inky**: The blue ghost uses a combination of Blinky and Pac-Man’s position to determine its movement.
- **Clyde**: The orange ghost switches between chasing Pac-Man and wandering randomly.

## 📦 Assets
- **Sprites**: All player and ghost sprites are stored in the `assets/` folder.
- **Sound Effects**: You can add sound effects for movement, power-ups, and win/lose conditions.

## 🚩 Future Improvements
- Sound effects integration for a more immersive experience.
- A scoring system displayed in the top corner.
- Enhanced ghost AI to make the game even more challenging!

## 🛠️ Contributing
Feel free to fork this repository and contribute by submitting a pull request. Let's make Pac-Man even better together!

## ⚖️ License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

