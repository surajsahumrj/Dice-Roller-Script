# Dice Roller Script

This repository contains a Python script that simulates rolling a six-sided die using an image containing different dice faces.

## Features
- **Simulates a dice roll**: Randomly selects a dice face from an image.
- **Interactive command-line interface**: Prompts the user to roll the dice.
- **Displays corresponding dice face**: Uses `PIL` to crop and show the correct portion of the dice image.

## Prerequisites
- Python 3.x
- `PIL` (install using `pip install pillow`)

## Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```sh
   pip install pillow
   ```

## Usage
Ensure `dice.jpg` exists in the working directory, then run:
```sh
python dice_roller.py
```
Follow the prompt and type `ROLL` to roll the dice. The script will display the corresponding dice face.

## Notes
- The dice roller script uses an image of dice faces divided into sections, cropped dynamically based on a random roll.
- Modify `dice.jpg` accordingly if using a different image format.

## License
This project is licensed under the MIT License.

