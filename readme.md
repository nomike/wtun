# wtun - Wiener WohnTicket Update Notifier

This program fetches a list of all available flats on the Wiener WohnTicket website and notifies you via email if a new flat is available.

## Requirements

- Python 3.6+
- pip

## Usage

1. Clone this repository
2. Create a virtual environment with `python3 -m venv venv`
3. Activate the virtual environment with `source venv/bin/activate`
4. Install the requirements with `pip install -r requirements.txt`
5. Call the program with the appropriate arguments

## How to get the session cookie

1. Open the [Wiener WohnTicket website](https://wohnungssuche.wohnberatung-wien.at) in your browser.
2. Logim with your credentials.
3. Open the developer tools (F12) and go to the network tab.
4. Reload the page.
5. Click on the first request and copy the value of the `Cookie` header (it should be something like `PHPSESSID=...`). This is your session cookie.

