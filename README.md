# Asteroids

A simple Python arcade-style Asteroids game built with `pygame`.

## What this is

This repository contains a playable game that can run on Windows, macOS, or Linux. It is designed for a non-coder: just install Python, follow the setup steps, and launch the game.

## Requirements

- Python 3.13 or newer
- Internet access to download `pygame`
- A terminal or command prompt

## Setup

1. Open a terminal or command prompt.
2. Change into the game folder.

   macOS / Linux:
   ```bash
   cd ~/CodingWork/asteroids
   ```

   Windows:
   ```powershell
   cd %USERPROFILE%\CodingWork\asteroids
   ```

3. Create a Python virtual environment.

   macOS / Linux:
   ```bash
   python3 -m venv venv
   ```

   Windows:
   ```powershell
   python -m venv venv
   ```

4. Activate the virtual environment.

   macOS / Linux:
   ```bash
   source venv/bin/activate
   ```

   Windows:
   ```powershell
   venv\Scripts\activate
   ```

5. Install the game dependency:

   ```bash
   pip install -r requirements.txt
   ```

   If you do not have `requirements.txt`, run:

   ```bash
   pip install pygame==2.6.1
   ```

6. Verify Python is available by running:

   ```bash
   python --version
   ```

   If that shows an error, try:

   ```bash
   python3 --version
   ```

## Run the game

With the virtual environment active, start the game:

```bash
python main.py
```

## Game controls

- `A` = rotate left
- `D` = rotate right
- `W` = move forward
- `S` = move backward
- `Space` = shoot
- Close the game window to exit

## Troubleshooting

- If `python` or `pip` is not found, try `python3` instead.
- If the game does not start, make sure the virtual environment is active.
- If `pygame` fails to install, check your internet connection and retry the install command.

## Thanks

Thanks to boot.dev for inspiration and resources.
