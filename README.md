# Appointment Booking Automation

![Workflow](Appointment%20Booking.png)

An automated appointment booking system for small businesses built with n8n and Tally.

## What it does
- Customer fills a Tally booking form
- Instantly receives a confirmation email
- Gets a reminder email 24 hours before appointment
- Receives a follow up email after appointment

## Tools Used
- n8n — workflow automation
- Tally — booking form
- Gmail — email delivery

## How it works
1. Customer submits booking form on Tally
2. Tally sends data to n8n via webhook
3. n8n triggers confirmation email immediately
4. n8n waits and sends reminder 24hrs before appointment
5. n8n follows up 4hrs after appointment

## Use Cases
Salons, clinics, consultants — any small business that takes appointments
