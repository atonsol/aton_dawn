# Dawn Validator Bot
Automation farming Script for Dawn Validator using proxies. This bot support multi accounts.
### Tools and components required
1. Dawn Validator Account | Download [Dawn Validator Extension](https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp)
2. Open ``chrome-extension://fpdkjdnhkakefebpekbdhillbhonfjjp/signup.html``, insert Referral code ``08rwg8kb`` and Register
3. Python version 3.10
## Getting Token
- Open ``chrome-extension://fpdkjdnhkakefebpekbdhillbhonfjjp/dashboard.html`` in your browser and login
- Press F12 or CTRL+SHIFT+I and Select Network
- Look for ``getpoint?appid=`` as image. If it doesn't show "getpoint?appid" then press F5
- Open request headers and copy the token. Bearer ``a1b2c3d4ef5g`` < your token
- Insert your account details in ``accounts.txt``, with each line in the format ``email:token`` for each account, like:
```bash
email:token
email:token
email:token
```
# Installation
- Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)
- For Unix: ``apt install python3 python3-pip -y``
- Install requirements, Windows:
```bash
pip install -r requirements.txt
```
- Unix:
```bash
pip3 install -r requirements.txt
```
### Run the Bot
- Replace the proxies example in ```proxies.txt``` to your own proxies
#### Run for single account
- Windows:
```bash
python main.py
```
- Unix
```bash
python3 main.py
```
# Notes
- This bot have delay every 5 minutes. 
- You can buy Proxies Static Residental Vietnam via Zalo: 0358028338
