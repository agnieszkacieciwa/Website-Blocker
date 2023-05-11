# Website-Blocker

This is a Python script that allows you to block specific websites during certain hours of the day. 
It modifies the host's file on your system to redirect the blocked websites to a local IP address.

## Prerequisites

- Python 3.x
- `time` and `datatime` collections

## Usage

1. Make sure you have administrative privileges to modify the hosts file on your system.
2. Clone or download this repository to your local machine.
3. Open the website_blocker.py file in a text editor.
4. Modify the website_list variable to include the websites you want to block. Add or remove URLs as needed.
5. Adjust the time range in the if statement according to your preference. By default, the script blocks websites between 8 AM and 4 PM.
6. Run the script using Python.

## Note

- This script modifies the host's file on your system. Use it responsibly and only on your own machine.
- Make sure to run the script with administrative privileges to allow modifications to the host's file.
- The script will run indefinitely, continuously checking the time and updating the hosts file accordingly every 5 seconds. To stop the script, you can manually interrupt it (e.g., press Ctrl + C).
