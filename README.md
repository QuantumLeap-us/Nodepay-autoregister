# Nodepay Autoreferral Bot
Automatic referral script for Nodepay Account using captcha solver and proxies.
### Tools and components required
1. Nodepay Account | Register: [https://app.nodepay.ai/register](https://app.nodepay.ai/register?ref=43HG9DLooqGcwKj)
2. Captcha Solvers API keys, you need to recharge credits | [2captcha.com](https://2captcha.com/?from=22391145) | [capmonster.cloud](https://capmonster.cloud/) | [anti-captcha.com](https://getcaptchasolution.com/hjyoilkbhd)
(https://dashboard.ez-captcha.com/#/register?inviteCode=TvXBfsIZJGy) |[Recommended: Cheap EzCaptcha]
3. VPS or RDP (OPTIONAL)
4. Python version 3.10
# Installation
- Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)
- For Unix:
```bash
apt install python3 python3-pip -y
```
- Install requirements, Windows:
```bash
pip install -r requirements.txt
```
- Unix:
```bash
pip3 install -r requirements.txt
```
### Run the Bot
- Replace the proxies example in ```proxies.txt``` to your own proxies with format:
```bash
http://host:port
http://user:pass@host:port
```
>only http proxies support for now
#### Run command:
- Windows:
```bash
python main.py
```
- Unix
```bash
python3 main.py
```
- Insert your referral code, example: ``https://app.nodepay.ai/register?ref=XXXXXXXXXX`` this is your code: ``XXXXXXXXXX``
- Enter how many referrals you want, more referrals will result in more use of your captcha solver api credits
- Select your captcha solver service (Make sure you have credits, you can topup first)
- Select proxy usage yes or no
- Result account generated will be saved to ``accounts.txt``
# Notes
- Run this bot, and it will update your referrer code to my invite code if you don't have one.
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.
- Original: [im-hanzou](https://github.com/im-hanzou)
