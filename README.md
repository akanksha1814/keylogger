# Keylogger Project

This project implements a simple keylogger in Python, capable of capturing keyboard input and logging it to a file or sending it via email. The project also demonstrates the use of the pynput library for monitoring keyboard events.

## Features

- Captures keyboard input in real-time.
- Logs keystrokes to a file.
- Sends logged keystrokes via email.

## Installation

 Install the required dependencies:

    ```bash
    pip install pynput
    ```

## Usage

1. Modify the `execute_keylogger.py` file to set your email address and password for sending logs.
2. Run the `execute_keylogger.py` script:

    ```bash
    python execute_keylogger.py
    ```

3. The keylogger will start capturing keyboard input. Press the Escape key (Esc) to stop the keylogger and exit the program.
