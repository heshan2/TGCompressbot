---

## Video Compressor Bot

## Bot by Bhardwajji 



#### The Easy Way

  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/heshan2/TGCompressbot)

#### The Hard Way

```sh
virtualenv -p python3 VENV
. ./VENV/bin/activate
pip install -r requirements.txt
# <Create config.py with variables as given below>
python bot.py
```

An example `config.py` file could be:

**Not All of the variables are mandatory**

```python3
from sample_config import Config

class Development(Config):
  APP_ID = 6
  API_HASH = "0a22407a75b22e206c9b2c000aa89d26"
  TG_BOT_TOKEN = "1537958406:AAFiq7S3x93hXXdXx95wD_qK91oC9IZqDec"
  AUTH_USERS = [
    2449398
  ]
```

### [@BotFather](https://telegram.dog/BotFather) Commands

```
start - Checking bot live.
compress - To compress the video.
cancel - Stop the process.
log - Get log
help - To know about bot
```




#### LICENSE
- GPLv3
