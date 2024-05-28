# AFK Bot

This Python script utilizes the PyAutoGUI library to prevent the computer from going into an idle state by moving the mouse cursor periodically.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this game on your local machine, follow these steps:

1. **Clone the repository:**
    ```bash
    gh repo clone aFro95/AFK-Bot
    cd AFK-Bot
    ```

2. **Install the dependencies:**
    Make sure you have Python and pyautogui installed. You can install pyautogui using pip:
    ```bash
    pip install pyautogui
    ```

## Features
<ul><li>Moves the mouse cursor at random intervals to prevent the system from going idle.</li>
<li>Resets the idle counter whenever mouse movement is detected.</li></ul>

## Usage

To start the game, simply run the script:
```bash
python AFK Bot.py
```

## Configuration
Idle Counter Threshold: You can adjust the threshold for the idle counter by modifying the value of afk_counter > 5 in the script. This determines the number of consecutive cycles with no mouse movement before the cursor is moved.


Cursor Movement Speed: The speed of cursor movement can be adjusted by changing the duration parameter (0.5 in pag.moveTo(x, y, 0.5)). Lower values result in faster cursor movement.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork this repository.
2. Create a branch:
```bash
git checkout -b feature/new-feature
```
3. Commit your changes:
```bash
git commit -m 'Add some feature'
```
4. Push to the branch:
```bash
git push origin feature/new-feature
```
5. Create a pull request.

## License
This project is licensed under the MIT License.
