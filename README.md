# StarCraftRPG-Web

`StarCraftRPG-Web` is the web-based version of the StarCraftRPG game. This version brings the text-based RPG experience to a web interface, allowing players to interact with the game through a browser. The web version leverages Flask to serve as the backend API, which was originally part of the console game. A simple HTML file with JavaScript is used to provide the frontend.

## Overview

In StarCraftRPG-Web, you play as James Raynor, navigating a humorous and modified StarCraft storyline to rescue Sarah Kerrigan from a Zerg invasion on planet Tarsonis. This web-based version offers a similar experience to the console game but through a web interface.

## Features

- **Web Interface**: Play the game through a web browser with a simple HTML and JavaScript frontend.
- **API Backend**: The game uses a Flask-based backend API derived from the original console version.
- **Command-Based Interaction**: Input commands to interact with the game world, similar to the console version.
- **Humorous Narrative**: Enjoy a light-hearted twist on the StarCraft story with dynamic storytelling.

## Requirements

- **Python 3**: Ensure Python 3 is installed on your system.
- **Flask**: Install Flask using pip:
  ```bash
  pip install flask
  ```

## Installation

1. **Clone the Repository**:
   - Clone the StarCraftRPG repository using Git: 
    ```bash
   git clone https://github.com/cutiri/StarCraftRPG-Web.git
     ```
   - Navigate to the project directory:
     ```bash
     cd StarCraftRPG-Web
     ```

2. **Run the Web Server**:
   - Execute the game script using Python:
     ```bash
     python ./alta3research-flask01.py
     ```
3. **By default, the web portal should be accessible at http://127.0.0.1:2224.**

## How to Play

- **Authenticate**: Access the web portal and log in with one of the following credentials:
  Username: user1, user2, or user3
  Password: pass
- **Play the Game**: After authentication, type commands in the text input field and press ENTER. Commands include:
- **View Commands**: Type `help` to see a list of available commands and their descriptions:
  - **`go [location]`**: Move to a different location.
  - **`get [item]`**: Retrieve an item from your surroundings.
  - **`attack [target]`**: Engage in combat with a specified target.
  - **`assist [character]`**: Provide help to another character.
  - **`cheat [code]`**: Unlock special features or gain advantages in the game. Yes I implemented some of the origial StarCraft cheat codes, if you are a real fan you won't have problem finding them.
  - **`help`**: Display a list of available commands.

## What is This

A web-based RPG game based on the StarCraft video game. It features a simple web frontend and a Flask-based API backend, providing a similar experience to the console version of the game.

## Screenshots

- Check the picture files inside the _screenshots folder to see how the web interface looks.

## Console Version

For the console version of the game, visit [StarCraftRPG-Console](https://github.com/cutiri/StarCraftRPG-Console).

## License

The StarCraftRPG project is licensed under the [MIT License](#). See the LICENSE file for more details.

## Contact

For questions or support, please contact us at [avillasante@hotmail.com](mailto:avillasante@hotmail.com).
