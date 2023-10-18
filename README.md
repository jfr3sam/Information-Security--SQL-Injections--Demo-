# Demo Project

This README provides step-by-step instructions for setting up a Python virtual environment across different operating systems. The guide also includes additional tips for working with Flask and SQLite.

## Table of Contents

1. [Setting Up a Virtual Environment](#setting-up-a-virtual-environment)
2. [Activating the Virtual Environment](#activating-the-virtual-environment)
3. [Working with Flask](#working-with-flask)
4. [Working with SQLite](#working-with-sqlite)

## Setting Up a Virtual Environment

### Windows

1. **Open Command Prompt**: Press `Windows + R`, type `cmd`, and hit Enter.
2. **Navigate to Project Directory**: Use the `cd` command to navigate to your project folder.
3. **Create Virtual Environment**:  
    ```cmd
    python -m venv myenv
    ```

### macOS and Linux

1. **Open Terminal**: Open it from the Applications folder or search for it using Spotlight (`Cmd + Space`).
2. **Navigate to Project Directory**: Use the `cd` command to go to your project folder.
3. **Create Virtual Environment**:  
    ```bash
    python3 -m venv myenv
    ```

## Activating the Virtual Environment

### Windows

1. **Activate Virtual Environment**:  
    ```cmd
    .\myenv\Scripts\Activate
    ```

### macOS and Linux

1. **Activate Virtual Environment**:  
    ```bash
    source myenv/bin/activate
    ```

## Working with Flask

1. **Install Flask**:  
    ```bash
    pip install Flask
    ```
2. **Run Flask Application**:  
    ```bash
    flask run
    ```

## Working with SQLite

1. **Install SQLite**:  
    ```bash
    pip install sqlite
    ```
2. **Initialize Database**:  
    ```bash
    python init_db.py
    ```

