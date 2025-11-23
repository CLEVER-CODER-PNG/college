Project Overview


This Python project allows the user to schedule WhatsApp messages that will be automatically sent through the Twilio WhatsApp API at a date and time determined by the user.
This script will gather the recipient's information, the message content, and the send time. It will then wait until the appointed time comes to send the message across.

This tool is helpful for:

⦁	Sending reminders

⦁	Birthday or event messages

⦁	Automated notifications

⦁	Personal productivity tools


Features

⦁	 Send WhatsApp messages through Twilio
⦁	 Schedule messages for a future date and time
⦁	 Simple command-line interface
⦁	 Error-handling for invalid date/time inputs
⦁	 Easy to modify and integrate into other applications

Technologies / Tools Used

⦁	Python 3

⦁	Twilio Python SDK (twilio)

⦁	datetime module (for scheduling)

⦁	time module (to delay execution)


Set Up Your Twilio Account

1.Create a free account at https://www.twilio.com

2.Activate the WhatsApp Sandbox

3.Get your:

⦁	ACCOUNT_SID
⦁	AUTH_TOKEN


How to Run the Project
Execute the script:



Then follow the on-screen prompts:

1.	Enter recipient name

2. Enter their WhatsApp number in full international format

3. Enter your message

4. Enter schedule date & time

The script will wait until the target time and send the message automatically.


Testing Instructions

To test properly:

1.Ensure your Twilio WhatsApp Sandbox is joined
(usually by sending a code like join xxxx to the Twilio number).

2.Use your own WhatsApp number first to confirm messages work.

3.Try scheduling:

⦁	A message 1–2 minutes in the future

⦁	A message with an incorrect date to test validation

4.Verify the message appears in your WhatsApp app.

SCREENSHOTS
You can include image such as

CLI input example
https://github.com/CLEVER-CODER-PNG/college/blob/141e81cf820272948bbb09a9796fd40e7a4e2d44/Screenshot%202025-11-23%20112620.png


Twilio Dashboard Logs Screenshot
(Insert image showing message logs)


