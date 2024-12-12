# LinkedIn Company Page Bot

This bot manages and automates posting content to your LinkedIn company page using Ollama for AI-generated content.

## Features

- AI-powered content generation using Ollama
- Automated posting to LinkedIn company page
- Configurable posting schedule and content topics
- Data-driven content creation
- Image management for posts

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Configure the bot:
- Edit `config/config.json` with your LinkedIn credentials and Ollama settings
- Add your LinkedIn access token and company page ID
- Configure the Ollama host and model settings
- Customize the content topics and posting schedule

3. Add images:
- Place your post images in the `assets/images` directory

## Usage

Run the bot:
```bash
python src/linkedin_bot.py
```

## Configuration

The `config.json` file contains:
- LinkedIn API credentials
- Ollama settings
- Content persona configuration
- Topics for content generation
- Posting schedule

## Directory Structure

```
├── config/
│   └── config.json
├── src/
│   └── linkedin_bot.py
├── assets/
│   └── images/
├── data/
└── requirements.txt
```
