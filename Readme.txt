💧 Water Drinking Reminder

A simple Python project that sends desktop notifications every hour to remind you to drink water and stay hydrated while studying or working.

✨ Features
💧 Sends desktop notifications with a friendly water reminder.
⏰ Repeats automatically every 1 hour.
🐍 Built with beginner-friendly Python code.
🔔 Uses desktop notifications through the Plyer library.
🛠️ Technologies Used
Python
time module
plyer library
📥 Installation

1. Install Python

Download Python from python.org if it isn't already installed.

2. Install Plyer

Open your terminal and run:

bash
pip install plyer


3. Download this repository

Clone the repository:

bash
git clone YOUR_REPOSITORY_URL


Replace YOUR_REPOSITORY_URL with your actual GitHub repository URL.

Alternatively, download the repository as a ZIP file from GitHub.

▶️ How to Run

Open the project folder in your terminal and run:

bash
python water_reminder.py


A desktop notification will appear with this message:

💧 Go grab some water so your brain keeps working its magic!

The first notification appears immediately. The next reminder appears after one hour.

To stop the program: Press Ctrl + C in the terminal.

⏰ Customize the Reminder Interval

You can change the interval by modifying time.sleep() in the Python file.

python
time.sleep(3600)  #  For 1 hour
time.sleep(7200)  #  For 2 hours


