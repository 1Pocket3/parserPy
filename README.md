# Telegram Group Parser

A Python script for parsing messages and members from a Telegram group using Telethon.

## Requirements

- `xmlrpc.client`
- `telethon`

Configuration
Before running the script, you need to provide your Telegram API credentials and phone number in the code. Update the following variables in the script:
```python
api_id = INSERT UR ID
api_hash = 'INSERT UR HASH'
phone = 'INSERT UR PHONE'
```
## Usage

+ Run the script using a Python interpreter.

+ The script will prompt you to choose a group for parsing messages and members. Enter the corresponding number and press Enter.

+ The script will start retrieving the members of the selected group and save them in a CSV file named members.csv.

+ After retrieving the members, the script will start parsing the messages of the selected group and save them in a CSV file named chats.csv.

+ Once the process is complete, you will see the success messages indicating that the parsing of members and messages was done successfully.

