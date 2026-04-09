# Go High Level (GHL) CRM Setup

## Pipeline Stages
- New Lead
- Contacted
- Appointment Booked
- Consultation Done
- Won
- Lost

## Workflow 1: Welcome Automation
Trigger: New Lead Created

Actions:
- Send welcome email
- Send SMS with booking link
- Follow-up after 24 hours
- Final reminder after 48 hours
- Move to Lost after 5 days

## Workflow 2: Appointment Booking
Trigger: Appointment Booked

Actions:
- Move contact to "Appointment Booked"
- Send confirmation email
- Send reminder SMS (24h & 1h before)

## Workflow 3: Post Consultation
Trigger: Consultation Done

Actions:
- Send thank-you email
- Follow-up after 3 days
