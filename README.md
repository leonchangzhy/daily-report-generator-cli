# Daily Report Generator CLI
A simple CLI that generates the daily report based on the google calendar API v3.
Code was implemented using help of ChatGPT

# Preparation
- Create a service account on GCP and dowload the key as json, put it in credential.json
- Create a .env file from [.env.example](.env.example), replace the email with the account you want to fetch events from

# Installation

```bash
 $ pip install -r requirements.txt
```

# Run
```bash
 $ ./main
```