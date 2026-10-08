# Hotel Guest Assistant: Respond to Guest Inquiries via Email and WhatsApp

An automation built in Zapier that reads each guest form response, sorts it by type, and replies to the guest through both Gmail and WhatsApp, with no one typing the replies by hand.

!(https://github.com/miracle003-hub/Hotel-Guest-Assistant/blob/main/zap2e.png)

## The problem

Hotel guests send booking confirmations, general questions and urgent complaints through the same channel. Handling them by hand is slow, and an urgent complaint can sit behind routine requests.

## How it works


1. **Trigger:** a guest submits the Hotel Guest Assistant Google Form (Google Forms, *New Form Response*).
2. **Sort:** a *Paths* step splits every response into one of three paths using path conditions:
   - **Confirmed Booking**
   - **General Question**
   - **Urgent Problem/Complaints**
3. **Reply by email:** on each path, Gmail sends the guest a reply (*Send Email*).
4. **Reply by WhatsApp:** on each path, WhatsApp Notifications sends the guest a message (*Send Message*).

Each path has its own email and WhatsApp message, so the guest gets a reply that fits what they asked, and urgent problems are handled separately from routine requests.

## Tools used

- Zapier (Zap with Paths)
- Google Forms
- Gmail
- WhatsApp Notifications (Zapier app)

## Testing

I tested the Gmail and WhatsApp steps in the Zapier editor. Zapier reported that the messages were sent successfully.

## What I practised

- Designing a multi-path workflow with conditions
- Connecting forms, email and messaging apps without code
- Writing a different reply for each type of guest request
- Testing each step before publishing

## Ideas for improvement

- Save every response and the path it took to a Google Sheet for reporting
- Notify a staff member immediately when the Urgent Problem/Complaints path runs

## About me

I am Ikechukwu Miracle Amarachi, a data analyst and AI automation builder.

- Portfolio: https://meerawebanalytics.com.ng
- LinkedIn: https://www.linkedin.com/in/miracle-ikechukwu-data
