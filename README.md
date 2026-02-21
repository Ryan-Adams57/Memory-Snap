# Memory-Snap

No coding required – Save your Snapchat memories directly to an external drive!

# Backup Your Snapchat Memories

Snapchat now enforces a 5GB limit on Memories, which means to create a full backup, you need to download your memories manually. This Python script lets you automatically download all your Snapchat memories from a JSON export.

# Getting Your Snapchat Data

Open Snapchat and navigate to Settings → My Data.

Request your Memories and choose JSON format.

Snapchat will email you a ZIP file containing your exported data.

Extract the ZIP and locate the memories_history.json file for use with this script.

# How It Works

1. Export your Snapchat memories as a JSON file.

2. Run the script in your terminal:

python3 download_snapchat.py

3. When prompted, drag your memories_history.json file into the terminal and press Enter.

4. When prompted, drag the folder where you want your memories saved and press Enter.

5. The script will start downloading all your media automatically!

# Requirements

Python 3.x

Internet connection (to download media files)

urllib (included with Python)

Access to your Snapchat JSON export

# Troubleshooting

❌ “File not found” error

Cause: Incorrect JSON file path

Fix: Drag the file into the terminal instead of typing the path manually.

❌ JSONDecodeError

Cause: Wrong file selected

Fix: Make sure you are using memories_history.json — not a folder, ZIP, or HTML file.

❌ HTTP Error 403: Forbidden

Cause: Snapchat links expire or have limited usage

Fix: If you run the script some time after exporting, re-export a fresh JSON from Snapchat and run the script again.
