# **_it's over_**
With the release of Claude Opus 5.5, coding is now over. This repo is a snapshot in case in the future I want to look back at some of my old hand-written code, though much of the 2025 onwards commits were influenced by Claude 4.x models.

# zhenpai

Community discord bot for people who #pretend-to-learn-to-code. [Invite Link](https://discord.com/api/oauth2/authorize?client_id=670839356872982538&permissions=4398046511089&scope=bot)

Currently hosting and deploying to [Railway](https://railway.app/)

## Running locally

Requires at least python 3.8.

Create your own `.env` file based on `.env.example`. You can create a bot and grab the token from the [Discord Developer Portal](https://discord.com/developers/applications)

Create venv: `python3 -m venv myenv`

Activate venv: `source myenv/bin/activate`

Install packages: `pip install --no-cache-dir -U -r requirements.txt`

Run: `python3 start.py`.

Deactivate venv: `deactivate`
