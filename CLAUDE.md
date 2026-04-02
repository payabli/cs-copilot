# Team 12 — AI Hackathon 2026

## Team
- Evelio
- Luis Trista
- Vamsi
- William Corbera
- Rupal

## Project: AI-Assisted Ticket Resolution for Customer Support

### Problem
When a client reports a transaction/payment issue, CS can't query the API or DB directly. Every complex ticket gets escalated to SRE/engineering, slowing resolution and pulling technical resources into support work.

### Flow
CS receives client request → CS creates ticket → AI generates context and resolution path

### What the AI handles
1. **Executive summary** of the client's recent activity
2. **API calls** to pull relevant transaction/payment data based on the ticket
3. **DB queries** for info not exposed via the API (e.g., backend decline reasons)
4. **Platform health summary** for the timeframe around the reported issue
5. **Draft response** for CS to send to the partner

## Stack (tentative — may change)
- Python + Streamlit
- Claude API for AI

## Build & Run
TBD

## Code Style
TBD
