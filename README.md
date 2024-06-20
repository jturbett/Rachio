
# Rachio Irrigation Script

This repository contains a Python script, `start_zones.py`, that interacts with the Rachio irrigation system API to control your sprinkler zones. The script reads OAuth credentials and person ID from local files, starts specified zones for specified durations, and sends notifications to a Microsoft Teams channel.

## Features

- Starts zones 1, 2, 3, and 4 for 3 minutes each.
- Starts zone 5 for 20 minutes.
- Sends a notification to a Microsoft Teams channel at the start and after each zone is completed.
- Reads OAuth key, person ID, and Teams webhook URL from local files.

## Prerequisites
-Rachio watering system
Download and store in local directory a text file for each 
-key.txt should contain your OAuth key without any extra spaces or newlines.
-personid.txt should contain your person ID without any extra spaces or newlines.
-teams.txt should contain your Microsoft Teams webhook URL without any extra spaces or newlines.
Python 3.x
requests library (install using `pip install requests`)

start script with python3 start_zones.py

or add it to your crontab to schedule each moring at 4 am to run

