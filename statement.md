Problem statement

Many users would like to schedule WhatsApp messages to be sent on a future date and at a specific time for reminders, greetings, birthday messages, meeting alerts, and follow-ups.
WhatsApp does not have a built-in scheduler, and sending messages at specific times can sometimes be either too inconvenient or just impossible.

This project solves that problem by using Python and the *Twilio WhatsApp API*, automatically sending a message at a date and time specified by a user. The system gathers the user's input recipient, message, and schedule time, waits until the moment of said schedule, and then sends that message programmatically.

Scope of the Project

The scope of this project includes:

Sending WhatsApp messages using the Twilio API.
Providing a command-line interface for user input.
Allowing users to set a future date and time for message delivery.
Calculating the delay between the current time and the scheduled time.
Automatically sending the message at the exact scheduled moment.
Handling basic errors and invalid scheduling attempts.

Target Users

This tool is designed for:

Individuals who want to schedule reminders or greetings on WhatsApp.
Students and beginners learning Python automation.
Developers exploring the Twilio WhatsApp API.
Small businesses needing automated WhatsApp notifications.
Anyone who wants to automate scheduled messaging without building a full application.

High-Level Features

User Input for Message Details

The program collects:

Recipient name
Recipient WhatsApp number
Message content

Scheduling System

The user specifies:

Date (YYYY-MM-DD)
Time (24-hour HH:MM format)

The system calculates the exact time difference and schedules the message.

Automatic Message Delivery

At the scheduled moment, the program automatically:

Connects to Twilio
Sends the WhatsApp message
Confirms delivery via console output

Error Handling

The system checks:

If the scheduled time is in the past
Invalid data formats
API/connection errors

Twilio API Integration

Uses Twilio’s WhatsApp Sandbox to send messages safely and reliably.
