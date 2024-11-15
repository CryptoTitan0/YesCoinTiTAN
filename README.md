# YesCoinTiTAN

AUTO CLAIM FOR YESCOIN / @Yescoin

[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Crypto_Titan0)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CryptoTitan0)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Crypto_Titan0)

# Table of Contents
- [YesCoinTiTAN](#YescoinTitan)
- [Warning](#warning)
- [Available Features](#available-features)
- [Registration](#registration)
- [How to Use](#how-to-use)
  - [Command Line Options / Arguments](#command-line-options--arguments)
  - [About Proxies](#about-proxies)
  - [Windows](#windows)
  - [Linux](#linux)
  - [Termux](#termux)
- [Viewing Reports](#viewing-reports)
- [Thank You](#thank-you)



# Warning

All risks are borne by the user

# Available Features

- [x] Auto 1x Tap
- [x] Auto Claim Task
- [x] Auto Join Squad Ghalibie
- [x] Auto Upgrade Fill Rate
- [x] Auto Upgrade Multi Value
- [x] Can Set Max Level (default 5)
- [x] Auto Use Energy Refill
- [x] Auto Use Chest
- [x] Auto Get Free Chest
- [x] Multi Account

# Registration

Click the following link to register: [https://t.me/yescoinCryptoBot/](https://t.me/theYescoin_bot/Yescoin?startapp=6YFT2o)

# How to Use

## Command Line Options / Arguments

This script/program supports several argument parameters that can be used. Here's an explanation of the arguments:

`--data` / `-D`: Used when you have a different filename for storing account data. By default, the filename used by this script/program to store account data is `data.txt`. For example, if you have a file named `query.txt` as the file storing account data, just run `bot.py` with the `--data` / `-D` argument. Example: `python bot.py --data query.txt`

`--proxy` / `-P`: Used when you have a different filename for storing the proxy list. The filename used by this script/program to store the proxy list is `proxies.txt`. For example, if you have a file named `prox.txt` as the file storing the proxy list, you just need to add the `--proxy` / `-P` argument parameter to use your proxy file. Example: `python bot.py --proxy prox.txt`
## Termux

1. Make sure your device has Python and Git installed.

    Recommendation: Use Python version 3.8+ (3.8 or newer)
   
   Python
   ```shell
   pkg install python3
   ```
   Git
   ```shell
   pkg install git
   ```

2. Clone this repository.
   ```shell
   git clone https://github.com/CryptoTitan0/YesCoinTiTAN.git
   ```

3. Enter the BluTitan folder
   ```
   cd YesCoinTiTAN
   ```

4. Install the required modules/libraries.
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit the `query.txt` file, enter your query data into the `query.txt` file. One line for 1 account, if you want to add a 2nd account, fill it in on a new line.

6. Run the program/script.
   ```
   python bot.py
   ```

# Viewing Reports

To view a report of the total balance of all accounts you can run a file called `report.py`


## How to get tgWebAppData (query_id / user_id)

1. Login telegram via portable or web version
2. Launch the bot
3. Press `F12` on the keyboard 
4. Open console
5. Сopy this code in Console for getting tgWebAppData (user= / query=):

```javascript
copy(Telegram.WebApp.initData)
```

6. you will get data that looks like this

```
query_id=AA....
user=%7B%22id%....
```
7. add it to `data.txt` file or create it if you dont have one


You can add more and run the accounts in turn by entering a query id in new line like this:
```txt
query_id=xxxxxxxxx-Rxxxxujhash=cxxx
query_id=xxxxxxxxx-Rxxxxujhash=cxxxx
```


# Error Table

| Error                 | Description                                                                                                                          |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| failed get json error | This is because the server response is not in JSON format and may be in HTML. You can check the server response in the http.log file |
| failed get task list  | This is because the server response doesn't provide the expected response. You can check the server response in the http.log file    |
| cannot start game     | Similar to the above error, this is due to the server. You can check the server response in the http.log file                        |

## This bot helpfull?  Please support me by buying me a coffee: 
``` 0xc4bb02b8882c4c88891b4196a9d64a20ef8d7c36 ``` - BSC (BEP 20)

``` UQBiNbT2cqf5gLwjvfstTYvsScNj-nJZlN2NSmZ97rTcvKz0 ``` - TON

``` 0xc4bb02b8882c4c88891b4196a9d64a20ef8d7c36 ``` - Optimism

``` THaLf1cdEoaA73Kk5yiKmcRwUTuouXjM17 ``` - TRX (TRC 20)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For questions or support, please contact [CUCUMBER TG CHAT](https://t.me/cucumber_scripts_chat)

# Thank You
