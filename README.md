# ps5-bot

PS5 order snipe bot

# How-to

1. Modify app.py 

- Fill in lines 40 - 48 with order payment information.

- Enable/disable headless mode on line 52. Headless mode disabled is only supported when running on MacOS.

2. Deploy using Docker

```
docker build . -t bot
docker run -t -i bot
```

3. Deploy using MacOS

``
brew cask install chromedriver
pip3 install -r requirements.txt
python3 app.by
``