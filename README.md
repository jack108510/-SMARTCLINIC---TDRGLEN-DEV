# Tudor Glen Invoice Dashboard

A real-time invoice and revenue tracking dashboard for Tudor Glen Clinic.

## Features

- 📊 Real-time invoice data visualization
- 💰 Revenue tracking and analytics
- 📅 Period filtering (Last Week, Last Month, Last Year)
- 🤖 AI Query Assistant for data insights
- 📈 Interactive charts with Chart.js

## How to Run Locally

1. **Start the server:**
   ```bash
   cd "Tudor Glen - Dev server"
   python3 server.py
   ```

2. **Open in browser:**
   - The server will automatically open `http://localhost:8000`
   - Or manually navigate to `http://localhost:8000`

## Live Site

This dashboard is hosted on GitHub Pages at: [View Live Site](https://jack108510.github.io/-SMARTCLINIC---TDRGLEN-DEV/)

## Webhook URLs

- **Invoice Data Webhook**: `https://jackwilde.app.n8n.cloud/webhook/60e42850-6593-4d18-a4c7-c38293d1d768`
- **AI Query Webhook**: `https://jackwilde.app.n8n.cloud/webhook/dfd8f0c4-c739-4c8b-a772-48c2040cfc83`

## Requirements

- Python 3.x (for local server)
- Modern web browser

## Notes

- The dashboard requires a local web server to avoid CORS issues when running locally
- When hosted on GitHub Pages, the webhooks may still have CORS restrictions depending on the webhook server configuration

