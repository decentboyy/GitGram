[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/decentboyy/GitGram)

# GitGram - Github Integration for Telegram Bot API

## Setup:
- Install all requirements, `pip3 install -r requirements.txt`
- Copy `config.sample.py`, edit and save as `config.py`
- Run `python3 GitGram.py`

## Deploy on Heroku:
If you want to deploy this app on Heroku, there's a one-click setup for that. Click below, fill up the form and hit **Deploy App**.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/decentboyy/GitGram)

### Prefer to use Auto-Deploy?

- Fork this repository, as you would do with other repos.
- Sign in to Heroku and create a new app.
- Open your app's overview. Under **Deploy** tab, select **Deployment method** to `GitHub`, connect your repo
- Select `master` to enable auto-deploys.
- Then on **Settings** tab, add `APP_URL`, `BOT_TOKEN`, `GITGRAM_SUPPORT`, `GIT_REPO_URL`, and `PROJECT_NAME` variables. To use them, set `ENV` to `True`.
- Just one restart away to run your instance. To setup, open your bot's PMs or add it to your group and use `/connect` command.

## Try on Gitpod:
1. [Login to Gitpod](https://gitpod.io/login).
2. [Open this repo in Gitpod](https://gitpod.io/#github.com/decentboyy/GitGram).
3. After workspace build, dependencies will be installed.
4. Follow step 2 and 3 in Setup section.
