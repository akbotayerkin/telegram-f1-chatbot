# Telegram F1 Chatbot

This is a Telegram chatbot that provides information about Formula 1 races, drivers, teams, and the 2025 Grand Prix schedule. It is built using Python and the `python-telegram-bot` library.

## 🏁 Features

- 📅 View upcoming Grand Prix races
- 🧑‍✈️ Get detailed profiles of F1 drivers
- 🏎️ Learn about F1 teams and their backgrounds
- 🗺️ Explore race tracks and locations
- ⚙️ Easy-to-use commands and fast responses

## 🚀 How to Run

1. **Download the code** from this repository.

2. **Install required packages** (open your terminal and run):

3. **Set your bot token**:
- Option 1: Edit the Python file and insert your token manually
- Option 2 (Recommended): Create a `.env` file and add this line:
  ```
  BOT_TOKEN=your_telegram_bot_token_here
  ```

4. **Run the bot**:

## 💬 Usage

Open Telegram, find your bot (via BotFather), and send these commands:

- `/schedule` – View upcoming races
- `/driver <name>` – Info about a specific driver
- `/team <name>` – Learn about F1 teams
- `/track <race>` – Details about a track

## 📁 Project Structure

project-folder/
├── bot.py
├── handlers/
│ ├── schedule.py
│ ├── drivers.py
│ └── teams.py
├── data/
│ ├── drivers.json
│ ├── teams.json
│ └── schedule.json
├── .env
├── requirements.txt
└── README.md

## 📌 Notes

- Don’t forget to **keep your bot token private**.
- If your token was pushed to GitHub, regenerate it in [BotFather](https://t.me/BotFather).

## 🤝 Contributing

Pull requests are welcome! If you have ideas or improvements, feel free to fork this repo and submit your changes.

## 📄 License

This project is licensed under the MIT License.
