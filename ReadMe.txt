This contains scripts for automating sending messages over WhatsApp Web or by using the Twilio API

DISCLAIMER:
I AM NOT RESPONSIBLE IF YOUR ACCOUNT GETS BANNED. CONSULT THE
TERMS AND CONDITIONS OF WHATSAPP AND PROCEED WITH CAUTION.
DON"T BE STUPID. DON'T DO ILLEGAL STUFF WITH MY CODE PLEASE.

https://www.whatsapp.com/legal/

NOTE:
    Run 'python sendMessage.py -h' or 'python sendMessage.py --help' for help menu

    The virtual environment "env" which ships with the program was made
    with Pop_OS! 20.04, and might not work on other distros. So if things
    don't work, this might be a reason why. Delete the env, create a new one
    and then install the required modules from "requirements.txt"

    Requires Chromium WebDriver and Python 3.6+ to work properly.
    If you come across any bugs, submit an issue. I'll work on fixing it.
    If you're able to fix the bug, then send a PR. I'll merge after review.

    UPDATE:
        - Added GeckoDriver support; Firefox should work now
        - Added Twilio Support; can now pass secrets.json as an argument to use it

Links:
    ChromeDriver install : https://chromedriver.chromium.org/getting-started
    GeckoDriver  install : https://github.com/mozilla/geckodriver
    Selenium (reference) : https://www.selenium.dev/
    Twilio (if using it) : https://www.twilio.com/docs/libraries/python

    If something doesn't work, StackOverFlow and Google are your friends.

Usage:
    Consult the 'examples' folder for details on usage

Python Dependancies:
    astroid==2.4.2
    certifi==2020.6.20
    chardet==3.0.4
    idna==2.10
    isort==5.4.2
    lazy-object-proxy==1.4.3
    mccabe==0.6.1
    PyJWT==1.7.1
    pylint==2.6.0
    pytz==2020.1
    requests==2.24.0
    selenium==3.141.0
    six==1.15.0
    toml==0.10.1
    twilio==6.45.0
    urllib3==1.25.10
    wrapt==1.12.1

This script was generated to automate sending messages for club recruitements
over whatsapp, as people are more likely to check whatsapp than email.

The WhatsApp app requrires the user to have the contact details of the recipient
saved in order to message them, which proves to be a pain when sending messages
to some 50+ students inviting them to attend in-person interviews.

Two alternatives to this mind-numbing task are: 
    1. Using WhatsApp web to send these messages, as it doesn't necessiraly require 
       the recipient's number to have been saved.
    2. Using the Twilio API to send the messages. But has a call limit in the free
       tier.

The script takes care of both cases. Run 'python sendMessage.py -h' for help.

This was made out of pure spite. Saving a bajilion numbers is mind-numbing. Please
don't make me ever do it again.

<3