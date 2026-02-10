# Automated Booking Calendar & CRM (n8n)

This project demonstrates how to build a completely free automated booking system without using paid tools like Calendly or HubSpot.

Whenever a meeting is created in Google Calendar, the event details are automatically stored in a Google Sheets-based CRM.

## 🔧 Tools Used
- n8n (workflow automation)
- Google Calendar (event trigger)
- Google Sheets (CRM storage)

## ⚙️ Workflow Overview
1. Google Calendar Trigger listens for new events
2. On event creation, meeting details are extracted
3. Data is appended as a new row in Google Sheets

## 📊 Use Case
- Service-based businesses
- Freelancers
- Coaches and consultants
- Anyone needing a free booking + CRM system

## 🧪 How to Test
1. Activate the workflow in n8n
2. Create a new event in Google Calendar
3. Check the Google Sheet for an automatically added row

## 📁 Files
- `automated-booking-calendar-n8n.json` → Exported n8n workflow

