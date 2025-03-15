# Whatsapp-stock-alert

**📌 Overview**

This project provides real-time WhatsApp alerts for specific stocks based on pre-defined trading strategies. We use the AngelOne Smart API for fetching stock market data and Interakt WhatsApp API to send alerts directly to WhatsApp.

**🚀 Features**

Fetch stock data in real-time using AngelOne Smart API.

Apply pre-coded trading strategies to filter relevant stock alerts.

Send instant WhatsApp notifications using Interakt API.

Scalable and customizable for different trading strategies.

**🛠️ Technologies Used**

Python (for automation & API integration)

AngelOne Smart API (for market data & trading execution)

Interakt WhatsApp API (for sending WhatsApp alerts)

Flask/FastAPI (for building API endpoints, if needed)

SQLite/PostgreSQL (for storing alert logs, if required)

**📌 Setup Instructions**

**Prerequisites**

An AngelOne Smart API account & API key

An Interakt API account & credentials

Python 3.x installed

Required dependencies installed

Installation Steps

Clone this repository:

git clone https://github.com/yourusername/whatsapp-stock-alerts.git
cd whatsapp-stock-alerts

Install dependencies:

pip install -r requirements.txt

Set up environment variables for API keys:

export ANGELONE_API_KEY="your_angelone_api_key"
export INTERAKT_API_KEY="your_interakt_api_key"

**Run the script:**

python main.py

**🔧 Configuration**

Modify strategies.py to customize stock selection criteria.

Update config.py with your AngelOne & Interakt API credentials.

**📝 Usage**

The script continuously monitors stock prices and applies trading strategies.

If a stock meets the criteria, an automated WhatsApp alert is sent.

Logs can be stored 
