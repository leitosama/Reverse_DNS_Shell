# DNShell v1.7


## Description:
  A Python Reverse Shell that uses DNS as the C2 channel.

## Install Server && Run
```bash
pip3 install -r requirements.txt
cp .env.sample .env
vim .env # Change <changeme>: secret,iv 
python3 
```


## Gotchyas:
  - don't forget to change your HOST
  - don't forget to change your SECRET key
  - run server first

## Moar Info:
  http://lockboxx.blogspot.com/2015/01/python-reverse-dns-shell.html
