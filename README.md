## Functionality
| Functional                                                     | Supported |
|----------------------------------------------------------------|:---------:|
| Multithreading                                                 |     ✅     |
| Collect Boots                                                  |     ✅     |
| Binding a proxy to a session                                   |     ✅     |
## [Settings](https://github.com/shamhi/TapSwapBot/blob/main/.env-example)
| Setup                   | Description                                                                |
|-------------------------|----------------------------------------------------------------------------|
| **API_ID / API_HASH**   | Platform data from which to launch a Telegram session (stock - Android)    | |
| **USE_PROXY_FROM_FILE** | Whether to use proxy from the `bot/config/proxies.txt` file (True / False) |

## Installation
You can download [**Repository**](https://github.com/AlexKutas/pocket-rocket-bot) by cloning it to your system and installing the necessary dependencies:
```shell
#Linux
~/pocket-rocket-bot >>> python3 -m venv venv
~/pocket-rocket-bot >>> source venv/bin/activate
~/pocket-rocket-bot >>> pip3 install -r requirements.txt
~/pocket-rocket-bot >>> cp .env-example .env
~/pocket-rocket-bot >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/pocket-rocket-bot >>> python3 main.py

#Windows
~/pocket-rocket-bot >>> python -m venv venv
~/pocket-rocket-bot >>> source venv/Scripts/activate
~/pocket-rocket-bot >>> pip install -r requirements.txt
~/pocket-rocket-bot >>> copy .env-example .env
~/pocket-rocket-bot >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/pocket-rocket-bot >>> python main.py
```

Also for quick launch you can use arguments, for example:
```shell
~/pocket-rocket-bot >>> python main.py --action (1/2/3)
# Or
~/pocket-rocket-bot >>> python main.py -a (1/2/3)

#1 - Create session
#2 - Run clicker
#3 - Run via Telegram
```
