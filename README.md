## Nevarevladim

Telegram Bot for sending whisper messages

### Requirements

- Python 3.8 or higher
- A [Telegram API key](https://docs.pyrogram.org/intro/setup#api-keys)
- A Telegram Bot created with [BotFather](https://t.me/BotFather)
  with "inline mode" and "Inline Feedback" enabled

### Setup

Create a new `config.ini`, copy-paste the following and replace the values with
your own

```
[pyrogram]
api_id = 18569832
api_hash = d309297b2b3741fdd173e2545c44b13a
bot_token = 5447158547:AAH2oDSvF5x9CCRjiaapbtr0tp4Y9ZhgDvE
```

Run the bot

```
virtualenv venv
venv/bin/pip3 install -U -r requirements.txt
venv/bin/python3 bot.py
```

### License

AGPL-3.0-or-later

```
ezWhisperBot, Telegram Bot for sending whisper messages
Copyright (C) 2021  Dash Eclipse

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
