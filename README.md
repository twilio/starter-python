# Welcome to the Python Guild!

As members of the Python guild, you will be working through the challenges of TwilioQuest using the Python programming language.  This project is pre-configured to do some interesting Twilio stuff using Python and the [Flask](http://flask.pocoo.org/) web framework.

## Setting Up

We assume that before you begin, you will have [Python](http://www.python.org/) and [pip](http://www.pip-installer.org/en/latest/) installed on your system and available at the command line.

Before you can run this project, you will need to make a copy of secrets.py.example and name it secrets.py. Edit secrets.py and change the string values as follows, and then save the file:

* `TWILIO_ACCOUNT_SID` : [Get it from your Twilio Console](https://www.twilio.com/console).
* `TWILIO_AUTH_TOKEN` : Same as above.
* `TWILIO_PHONE_NUMBER` : A Twilio number that you own, that can be used for making calls and sending messages.  You can find a list of phone numbers you control (and buy another one, if necessary) [in the console](https://www.twilio.com/console/phone-numbers/incoming).

## Running the application

1. Clone this repository. Navigate to the folder with the source code on your machine in a terminal window.

1. From there we recommend creating a [virtualenv](https://docs.python.org/3/library/venv.html) and activating it to avoid installing dependencies globaly on your computer.

    `virtualenv -p python3 env`
    `source env/bin/activate`

1. Install dependencies:

    `pip install -r requirements.txt`

1. Run the web app:
    `python app.py`

1. Open the app in your [browser](http://localhost:5000/) 

1. Enter your mobile number in the fields provided, and test both SMS text messages and phone calls being sent to the mobile number you provide.  The web UI should look something like this:

![python guild](https://raw.githubusercontent.com/twilio/starter-python/master/static/python_shield256.png)

## Begin Questing!
This is but your first step into a larger world.  [Return to TwilioQuest](http://quest.twilio.com) to continue your adventure.  Huzzah!
