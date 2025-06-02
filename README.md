# Arcade Games Collection

A modern collection of arcade-style games built with Pygame. This repository features multiple games with a sleek launcher interface, providing a nostalgic gaming experience with modern code architecture.


## 🎮 Featured Games

### 🚀 Rocket Rumble
A fast-paced space shooter where players navigate through asteroid fields while battling enemy ships.

### 👾 Pixel Heist
A stealth-based puzzle game where players must navigate through security systems to steal valuable artifacts.

### ⚔️ Shadow Clash
A fighting game with unique characters, each with special abilities and combat styles.

### 🏎️ Time Warp Racers
A racing game with a twist - players can manipulate time to gain advantages on the track.

## 📋 Requirements

- Python 3.8+
- Pygame 2.5.0+
- python-dotenv 1.0.0+

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/arcade-games.git
   cd arcade-games
   ```

2. **Set up a virtual environment (recommended)**
   ```bash
   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   
   # On Windows
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r pygame_arcade_project/requirements.txt
   ```

## 🎯 How to Play

### Launch the Arcade Launcher
```bash
python pygame_arcade_project/run_launcher.py
```

### Run Individual Games Directly
```bash
# Rocket Rumble
python pygame_arcade_project/run_rocket_rumble.py

# Pixel Heist
python pygame_arcade_project/run_pixel_heist.py

# Other games can be launched from the main launcher
```

## 🎮 Controls

### General Controls
- **ESC**: Return to launcher/Exit game
- **Mouse**: Navigate menus

### Game-Specific Controls

#### Rocket Rumble
- **Arrow Keys**: Move ship
- **Space**: Fire weapons
- **Z**: Special ability

#### Pixel Heist
- **WASD**: Move character
- **E**: Interact with objects
- **Shift**: Sneak mode

#### Shadow Clash
- **Arrow Keys**: Move character
- **A/S/D**: Attack buttons
- **W**: Block

#### Time Warp Racers
- **Arrow Keys**: Drive
- **Space**: Activate time warp
- **Shift**: Boost

## 🏗️ Project Structure

```
arcade-games/
│
├── pygame_arcade_project/
│   ├── assets/                 # Shared assets (images, sounds, fonts)
│   ├── games/                  # Individual game modules
│   │   ├── rocket_rumble/      # Rocket Rumble game files
│   │   ├── pixel_heist/        # Pixel Heist game files
│   │   ├── shadow_clash/       # Shadow Clash game files
│   │   └── time_warp_racers/   # Time Warp Racers game files
│   ├── utils/                  # Shared utility modules
│   ├── arcade_launcher.py      # Main arcade launcher interface
│   ├── config.py               # Global configurations
│   ├── run_launcher.py         # Script to run the launcher
│   └── requirements.txt        # Python dependencies
│
└── venv/                       # Virtual environment (created during setup)
```

## 🛠️ Development

### Adding a New Game

1. Create a new directory in `pygame_arcade_project/games/`
2. Implement the required files:
   - `__init__.py`
   - `main.py` with a `run_game()` function
   - Game-specific assets and logic
3. Update `config.py` to include your game

### Code Architecture

- **Modular Design**: Each game is self-contained with its own assets and logic
- **Shared Utilities**: Common functions are available in the `utils/` directory
- **Launcher Integration**: Games are accessible through a central launcher interface

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Pygame community for the excellent game development library
- Contributors who have helped build and improve these games
- Open-source game assets creators

---

Enjoy the games! For issues, suggestions, or contributions, please open an issue or pull request.
