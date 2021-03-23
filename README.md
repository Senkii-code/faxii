# faxii
faxii is the nickname of a little thermal printer on my desk, and this repo has the source code for the Telegram bot that controls it.


### Required packages:
- python-telegram-bot
- escpos
- tinydb
- datetime
- Pillow
- time
- emoji
- ujson


## Features

- Prints text, images, stickers, and images disguised as documents
- Extracts URLs from text, and prints them as QR codes
- Prints images in portrait layout, unless they'd be super long, then it just prints them landscape
- Print license support, including grant/revoke rights for owner
- Is just generally pretty neat?


## To Do

- Image > ASCII art converter
- Haiku recognition
- Support for re-requesting a print license after it's been revoked
- More feedback for the user
- Logging
