# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands
- Install dependencies: `pip install -r requirements.txt`
- Run tests: `pytest`
- Run a single test: `pytest path/to/test_file.py`

## Architecture
The project is a Flask-based expense tracker application.
- `database/`: Contains database connection and initialization logic (`db.py`).
- `static/`: Stores frontend assets (JS, CSS).
- `templates/`: Contains HTML templates for the user interface (e.g., login, register).
- `requirements.txt`: Lists project dependencies including Flask and Pytest.

## Project State
The application is currently in the initial setup phase. The `database/db.py` file is a placeholder and needs to be implemented to handle SQLite connections, table initialization, and seeding.
