# YouTube Downloader Bot
![photo_2025-12-06_14-22-01](https://github.com/user-attachments/assets/d9ceef9d-e767-4aa1-963e-2c20d45d7cd5)

This is a professional YouTube downloader bot written in Python. It uses the `telebot` library to interact with users
via Telegram and the `pytube` library to download YouTube videos and audio.

## Features

- Download YouTube videos in various formats and resolutions.
- Extract audio from YouTube videos.
- Easy-to-use Telegram interface.
- Premium and free versions.
- Fast in performance
- And many more...

## Prerequisites

- Python 3.10+
- A Telegram bot token from BotFather
- Required Python main libraries:
    - `pyTelegramBotAPI` (telebot)
    - `pytube`
- Local Telegram Bot API From [Here](https://tdlib.github.io/telegram-bot-api/build.html)

## Installation

1. Set up your Telegram bot:
    - User [BotFather](https://core.telegram.org/bots#botfather) to create a new bot and get your bot token.

2. Clone the repository:
   ```bash
   git clone https://github.com/DiarTor/youtube-downlaoder.git
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Setup Bot Configurations:
    - Go to `config/tokens.py` to configure your bot as you need.
    - Go to `config/database.py` to replace the database address.

5. Set up Your Local Telegram API Server:
    - Go to [my.telegram.org](https://my.telegram.org/auth) to obtain your API-ID and API-HASH.
    - Now go to [tdlib.github.io](https://tdlib.github.io/telegram-bot-api/build.html) to build your local Telegram API
      server
    - After you installed your server make sure to placed it in the main directory of your project ex: (youtube-downloader/telegram-bot-api).
    - Then go to `telegram_bot_api_launcher.py` file and place your API-ID and API-HASH.
6. Set up Your Database:
   - Go to `bot/common/plans` and then run the file so your plans go inside your database table.
## Usage

1. Run the local server:
   ```bash
   python telegram_bot_api_launcher.py
   ```

2. Run The bot:
3. ```bash
   python main.py
   ```

3. Use the following commands and instructions to interact with the bot:
    - `/start`: Welcome message and instructions.
    - `/admin`: List of available admin commands.
    - You Can use the Bot buttons for more use

## Example

Here's an example of how to use the bot:

1. Send `/start` to the bot:
2. Send the link of YouTube video you want to download
3. Choose a method via InlineButtons
4. Done.

## Contributing

Feel free to open issues or submit pull requests if you find any bugs or have feature requests.

## Acknowledgments

- [Telebot (pyTelegramBotAPI)](https://github.com/eternnoir/pyTelegramBotAPI)
- [Pytube](https://github.com/nficano/pytube)
- [YouTube](https://www.youtube.com)

---

*Warning: Downloading videos from YouTube might violate their terms of service. Please ensure that you have the right to
download the content before using this bot.*

*Note: There is no gateway connected to the bot so basically the premium version can not be bought automatically.*
