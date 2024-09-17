# TonTon Bot

TonTon Bot is a script designed to automate certain tasks using multiple tokens and optional proxies. This README provides instructions on how to set up and run the script on both Windows and Mac/Linux systems.

## Prerequisites

- Python 3.7 or higher
- `pip` (Python package installer)
- `virtualenv` (optional but recommended)

## Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/tonton-bot.git
    cd tonton-bot
    ```

2. **Create a virtual environment:**

    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment:**

    - **Windows:**

        ```bat
        venv\Scripts\activate
        ```

    - **Mac/Linux:**

        ```sh
        source venv/bin/activate
        ```

4. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```

5. **Prepare configuration files:**

    - **[config.json]()**: Configuration file for the bot.
    - **[token.txt]()**: File containing tokens, one per line.
    - **[proxy.txt]()**: (Optional) File containing proxies, one per line.

## Running the Script

### Windows

1. **Run the script using `run.bat`:**

    ```bat
    run.bat
    ```

### Mac/Linux

1. **Run the script using [run.sh]():**

    ```sh
    ./run.sh
    ```

## Configuration

### [config.json]()

Example configuration:

```json
{
    "tap": 3,
    "use_proxy": true
}