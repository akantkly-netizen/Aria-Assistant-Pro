# Aria Assistant Pro

A Telegram assistant project (Python).

## Overview

Aria Assistant Pro is a Telegram-based assistant. This repository was cleaned up and now contains only this README as a fresh starting point.

## Tech stack

- Python
- Pyrogram (Telegram client library)
- aiohttp / requests
- edge-tts

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/akantkly-netizen/Aria-Assistant-Pro.git
   cd Aria-Assistant-Pro
   ```
2. Add your project files and a `requirements.txt`.
3. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
4. Configure your Telegram API credentials using environment variables (never commit them).

## Security

Never commit session files, API keys, or tokens to the repository. Use environment variables or a `.env` file listed in `.gitignore`.

## License

No license specified yet.
