###Telegram Group Parser
This Python script allows you to parse messages and members from a Telegram group using the Telegram API. It retrieves the messages and members of a specified group and saves them in separate CSV files.

Prerequisites
Before running the script, make sure you have the following requirements installed:

xmlrpc.client module
telethon library
You can install the required libraries using the following command:

pip install telethon
Configuration
Before running the script, you need to provide your Telegram API credentials and phone number in the code. Update the following variables in the script:

python
api_id = INSERT UR ID
api_hash = 'INSERT UR HASH'
phone = 'INSERT UR PHONE'
Usage
Run the script using a Python interpreter.

The script will prompt you to choose a group for parsing messages and members. Enter the corresponding number and press Enter.

The script will start retrieving the members of the selected group and save them in a CSV file named members.csv.

After retrieving the members, the script will start parsing the messages of the selected group and save them in a CSV file named chats.csv.

Once the process is complete, you will see the success messages indicating that the parsing of members and messages was done successfully.

Output
The script will generate two CSV files:

members.csv: Contains the usernames, names, and group name of the members in the selected group.

chats.csv: Contains the messages from the selected group.

Note: The CSV files will be encoded in UTF-8 format.

Feel free to modify the script according to your requirements or extend its functionality as needed.
