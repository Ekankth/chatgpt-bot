### chatgpt-bot

![Python Version](https://img.shields.io/badge/python-3.9-green?style=for-the-badge&logo=appveyor)
![Issues](https://img.shields.io/github/issues/TeamKillerX/chatgpt-bot?style=for-the-badge&logo=appveyor)
![Forks](https://img.shields.io/github/forks/TeamKillerX/chatgpt-bot?style=for-the-badge&logo=appveyor)
![Stars](https://img.shields.io/github/stars/TeamKillerX/chatgpt-bot?style=for-the-badge&logo=appveyor)

### Disclaimer
```
️                       ⚠️ WARNING FOR YOU ️ ️⚠️
   chatgpt is used to help your account activities on Telegram
   We are not responsible for what you misuse in this repository
   !  Be careful when using this repository!
   If one of the members misuses this repository, we are forced to ban you
   Never ever abuse this repository
```

### Deploy to Branch [Heroku]

1. <b>Go to github, your fork</b>
2. <b>Delete your fork. If you didn't fork, go to step</b>
3. <b>Fork repo.</b>
4. <b>edit</b> 👉 [config.py](https://github.com/ekankth/chatgpt-bot/blob/main/config.py)
5. <b>Go to heroku</b>
6. <b>Desktop view</b>
7. <b>Go to deploy tab</b>
8. <b>Connect your github account</b>
9. <b>Deploy Main branch.</b>

### Deploy to Heroku
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/ekankth/chatgpt-bot)


### Tutorial Vps
```console
Ekankth@Ubuntu~ $ git clone https://github.com/ekankth/chatgpt-bot
Ekankth@Ubuntu~ $ cd chatgpt-bot
Ekankth@Ubuntu~ $ pip3 install -r requirements.txt
Ekankth@Ubuntu~ $ nano config.py
Ekankth@Ubuntu~ $ python3 bot.py
```

### Docker-Compose Vps
```console
Ekankth@Ubuntu~ $ sudo apt update -y && sudo apt upgrade -y

Ekankth@Ubuntu~ $ sudo apt-get install -y ca-certificates curl wget gnupg lsb-release

Ekankth@Ubuntu~ $ sudo mkdir -p /etc/apt/keyrings && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

Ekankth@Ubuntu~ $ echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

Ekankth@Ubuntu~ $ sudo apt-get update -y && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin
Ekankth@Ubuntu~ $ mkdir chatgpt && cd chatgpt
Ekankth@Ubuntu~ $ wget https://raw.githubusercontent.com/TeamKillerX/chatgpt-bot/main/sample_config.env -O config.env && wget https://raw.githubusercontent.com/TeamKillerX/chatgpt-bot/main/docker-compose.yml
Ekankth@Ubuntu~ $ nano config.env 

// Fill allvar for it to work //

Ekankth@Ubuntu~ $ docker-compose up -d
Ekankth@Ubuntu~ $ docker-compose start
Ekankth@Ubuntu~ $ docker-compose logs chatgpt
```

### Library
* [Dan](https://github.com/pyrogram) For [Pyrogram](https://github.com/pyrogram/pyrogram)


### Contributors
<b>you can pull requests here</b>
https://github.com/TeamKillerX/chatgpt-bot/pulls

<a href="https://github.com/TeamKillerX/chatgpt-bot/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=TeamKillerX/chatgpt-bot" />
</a>


### Credits
```
https://github.com/TeamKillerX/chatgpt-bot
```
### Donate
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.buymeacoffee.com/randydev)
