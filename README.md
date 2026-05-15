# n8n Automation Projects

A collection of n8n workflows for my first project.

## Repository contents

- `Motivation Telegram Bot.json` — an n8n workflow that sends motivational messages to Telegram.

## Workflow overview

This workflow:

1. Starts manually.
2. Adds a `Pesan` field with an initial text value.
3. Checks whether the text contains the word `Expert`.
4. If it matches, the workflow fetches a random quote from `dummyjson.com`.
5. The result is formatted and then sent to Telegram.

## Requirements

- n8n
- Access to the Telegram Bot API
- Internet access to fetch quote data

## Usage

1. Open n8n.
2. Import the `Motivation Telegram Bot.json` file.
3. Connect your Telegram credentials.
4. Adjust the `chatId` if needed.
5. Run the workflow manually.

## Notes

- This file is an exported n8n workflow.
- You can adjust the message content, IF condition, or quote source as needed.
