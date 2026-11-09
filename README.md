
# Lush Lounge Chatbot

An AI host chatbot mockup for a lounge in Lagos. **Chinedu**, a warm, friendly host, chats with guests in English or Nigerian Pidgin and hands them off to WhatsApp for bookings and anything that needs a person.

> **Demo project.** Lush Lounge is a fictional business. All guests, bookings and messages are sample data.

## What it does

- Floating chat widget with a welcome message and quick replies (Book a table, Events, Talk to the manager)
- Short, natural replies that match the guest's language
- **"Continue on WhatsApp"** button that opens a chat with a pre-filled message
- Consent checkbox and privacy note; chats are saved only with the guest's consent
- Guests can type STOP to stop saving and follow-ups
- Password-protected admin page to review chats and bookings

## How Chinedu behaves

- Replies in under 25 words
- Never invents prices, opening hours, availability, visits or bookings
- Never promises discounts
- Says "the manager will confirm" when unsure
- Says he is an AI assistant if asked

## 90-day follow-up plan

A planned re-engagement sequence for guests who opted in:

| Day | Purpose |
|---|---|
| 0 | Thank-you and feedback |
| 2 | Friendly check-in |
| 7 | Something new, no ask |
| 14 | Gentle offer based on last order |
| 30 | "We miss you" |
| 45 | Real event highlight |
| 60 | Birthday greeting (only if provided with permission) |
| 90 | Ask whether they want updates |

Follow-ups stop when a guest replies, complains or opts out.

## Built with

- Lovable (web app and backend)
- Make and Telegram (automation prototype)
- WhatsApp click-to-chat link for the handoff

## Status

Work in progress. A WhatsApp Business API integration, so Chinedu can reply on WhatsApp automatically, is a possible next step.

## Privacy

No real guest data is stored in this repository. No API keys or secrets are committed. Use fake data if you test it.

## Author

Built by [Your Name](https://github.com/Kristinebuilds) · [Portfolio](https://christinebuilds.netlify.app)
