# Status Rotator

Status Rotator is a simple Discord bot that rotates the bot's status in a loop. It is built using `discord.py-self`, allowing you to run it with a self-bot token. The bot statuses are customizable via a `config.json` file.

## Features

- Rotates bot statuses in a loop
- Customizable statuses list
- Easy to set up and configure

## Requirements

- Python (version 3.10 or above)
- `discord.py-self` (Python library)
- `colorama` (Python library for colored terminal text)

## Installation

1. **Clone the repository** or download the source code.

    ```bash
    git clone https://github.com/AxZeRxD/Discord-Status-Rotator
    cd Discord-Status-Rotator
    ```

2. **Install the required Python packages**. You can do this by running the following commands:

    ```bash
    pip install discord
    pip install discord.py-self
    pip install colorama
    ```

    Alternatively, you can install all dependencies using the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

3. **Configure the bot** by creating a `config.json` file in the project directory. The file should look like this:

    ```json
    {
        "statuses": ["Status 1 (Aizer)", "Status 2 (Aizer)", "Status 3 (Aizer)"],  // ADD MORE IF YOU WANT 
        "rtsec": 2,
        "Token": [""]
    }
    
    ```

    - `token`: Your Discord token (self-bot token).
    - `statuses`: A list of statuses that the bot will rotate through.

4. **Run the bot** by executing the main script:

    ```bash
    python status.py
    ```

## Usage

Once the bot is running, it will start rotating through the statuses defined in the `config.json` file. The status will change automatically at intervals defined in the script.

## Contributing

Feel free to fork the repository, create a new branch, and submit a pull request. Contributions are welcome!

## License

This project is licensed under the GNU License. See the `LICENSE` file for more details.
