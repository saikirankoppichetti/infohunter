# InfoHunter

InfoHunter is a modular Python OSINT (Open Source Intelligence) suite for collecting and analyzing information about users, emails, and domains. It generates professional reports (PDF, JSON, etc.) and supports both interactive and automated workflows.

## Table of Contents

- Features
- Installation
- Quick Usage
- Supported Modules and Data Sources
- Requirements
- Contributing
- License
- Contact
- About the Developer

## Features

- Username analysis across social networks (Sherlock, Maigret, etc.)
- Email leak and password checks (HIBP, BreachDirectory, Holehe, IntelX, EmailRep, Snusbase, etc.)
- Public domain/company intelligence (WHOIS, DNS, Shodan, Hunter.io, etc.)
- Automation-ready: CLI parameters and bot/API integration
- Optional web frontend (Flask/Streamlit)

## Installation

1. Clone the repository:
   git clone https://github.com/saikirankoppichetti/InfoHunter.git

2. (Recommended) Create and activate a virtual environment:
   python -m venv venv

On Windows
venv\Scripts\activate

On Linux/Mac
source venv/bin/activate

3. Install requirements:
   pip install -r requirements.txt

4. Configure your API keys (for more data sources):

- Create a .env file in the root folder:
  ```
  HIBP_API_KEY=your_key
  BREACHDIRECTORY_API_KEY=your_key