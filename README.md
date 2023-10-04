# README.md

# FastAPI Application in AWS App Runner

This is a simple FastAPI application that provides a greeting endpoint and an endpoint to add two numbers together.
This pushes changes in the repo directly to AWS App Runner.

## Features

- A root endpoint that returns a greeting message.
- An endpoint that adds two numbers.

## Installation

1. Ensure you have Python 3.7+ installed. You can verify with:
    ```bash
    python --version
    ```

2. Clone the repository:
    ```bash
    git clone <your_repository_link>
    cd <repository_directory>
    ```

3. Create a virtual environment:
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows, use: .venv\Scripts\activate
    ```

4. Install the required packages:
    ```bash
    pip install fastapi[all] uvicorn
    ```

## Usage

To run the application:

```bash
python app.py
