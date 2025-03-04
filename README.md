# Stack Overflow Enterprise Search Logs
A Python script for Stack Overflow Enterprise that creates a report (CSV file) of users' search history. You can see an [example](https://github.com/StackExcahnge/so4t_search_log_report/blob/main/Examples/search_logs.csv) of what the output looks like in the Examples directory.

## Requirements
* Stack Overflow Enterprise and a user account with admin permissions
* Python 3.8 or higher ([download](https://www.python.org/downloads/))
* Operating system: Linux, MacOS, or Windows
* Chrome browser

## Setup
[Download](https://github.com/StackExchange/so4t_search_log_report/archive/refs/heads/main.zip) and unpack the contents of this repository

To install the required open-source libraries for Python:
* Open a terminal window (or, for Windows, a command prompt)
* Navigate to the directory where you unpacked the files
* Install the dependencies: `pip3 install -r requirements.txt`

## Usage
In a terminal window, navigate to the directory where you unpacked the script. 
Run the script using the following format, replacing the URL with your own:

`python3 soe_search_logs.py --url "https://SUBDOMAIN.stackenterprise.co"`

At the beginning of the script, a small Chrome window will appear, prompting you to log in to your instance of Stack Overflow Enterprise. After logging in, the Chrome window will disappear, and the script will proceed in the terminal window.

The script typically takes less than a minute to run. As it runs, it will continue to update the terminal window with the status. When the script completes, it will indicate that the CSV has been exported, along with the file name. You can see an [example](https://github.com/StackExchange/so4t_search_log_report/blob/main/Examples/search_logs.csv) of what the output looks like in the Examples directory.

## Support, security, and legal
If you encounter problems using the script, please leave feedback in the Github Issues. You can also clone and change the script to suit your needs. It is provided as-is, with no warranty or guarantee of any kind.

All data is handled locally on the device from which the script is run. The script does not transmit data to other parties, such as Stack Overflow.
