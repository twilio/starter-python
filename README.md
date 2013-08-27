# Welcome to the Python Guild!

As members of the Python guild, you will be working through the challenges of TwilioQuest using the Python programming language.  This project is pre-configured to do some interesting Twilio stuff using Python and the [Flask](http://flask.pocoo.org/) web framework.

## Setting Up

We assume that before you begin, you will have [Python](http://www.python.org/) and [pip](http://www.pip-installer.org/en/latest/) installed on your system and available at the command line.

Before you can run this project, you will need to set three system environment variables.  These are:

* `TWILIO_ACCOUNT_SID` : Your Twilio "account SID" - it's like your username for the Twilio API.  This and the auth token (below) can be found [on your account dashboard](https://www.twilio.com/user/account).
* `TWILIO_AUTH_TOKEN` : Your Twilio "auth token" - it's your password for the Twilio API.  This and the account SID (above) can be found [on your account dashboard](https://www.twilio.com/user/account).
* `TWILIO_NUMBER` : A Twilio number that you own, that can be used for making calls and sending messages.  You can find a list of phone numbers you control (and buy another one, if necessary) [in the account portal](https://www.twilio.com/user/account/phone-numbers/incoming).

For Mac and Linux, environment variables can be set by opening a terminal window and typing the following three commands - replace all the characters after the `=` with values from your Twilio account:

    export TWILIO_ACCOUNT_SID=ACXXXXXXXXX
    export TWILIO_AUTH_TOKEN=XXXXXXXXX
    export TWILIO_NUMBER=+16518675309

To make these changes persist for every new terminal (on OS X), you can edit the file `~/.bash_profile` to contain the three commands above.  This will set these environment variables for every subsequent session. Once you have edited the file to contain these commands, run `source ~/.bash_profile` in the terminal to set up these variables.

On Windows, the easiest way to set permanent environment variables (as of Windows 8) is using the `setx` command.  Note that there is no `=`, just the key and value separated by a space:

    setx TWILIO_ACCOUNT_SID ACXXXXXXXXX
    setx TWILIO_AUTH_TOKEN XXXXXXXXX
    setx TWILIO_NUMBER +16518675309

## Running the application

[Download the project source code directly](https://github.com/twilio/starter-python/archive/master.zip) or [clone the repository on GitHub](https://github.com/twilio/starter-python).  Navigate to the folder with the source code on your machine in a terminal window.

You will first need to install the application's dependencies. To install them  manually, type the following commands in your terminal:

    pip install twilio
    pip install flask

Now, you should be able to launch the application.  From your terminal, run `python app.py`.  This should launch your sinatra application on port 5000 - [visit that URL on your local host](http://localhost:5000/).  Enter your mobile number in the fields provided, and test both SMS text messages and phone calls being sent to the mobile number you provide.  The web UI should look something like this:

![python guild](http://demo.kevinwhinnery.com/upload/Welcome_to_the_Python_Guild%21-20130827-150203.png)

## Begin Questing!
This is but your first step into a larger world.  [Return to TwilioQuest](http://quest.twilio.com) to continue your adventure.  Huzzah!
