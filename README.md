# Uptime Kuma

<a target="_blank" href="https://github.com/louislam/uptime-kuma"><img src="https://img.shields.io/github/stars/louislam/uptime-kuma" /></a> <a target="_blank" href="https://hub.docker.com/r/louislam/uptime-kuma"><img src="https://img.shields.io/docker/pulls/louislam/uptime-kuma" /></a> <a target="_blank" href="https://hub.docker.com/r/louislam/uptime-kuma"><img src="https://img.shields.io/docker/v/louislam/uptime-kuma/latest?label=docker%20image%20ver." /></a> <a target="_blank" href="https://github.com/louislam/uptime-kuma"><img src="https://img.shields.io/github/last-commit/louislam/uptime-kuma" /></a>  <a target="_blank" href="https://opencollective.com/uptime-kuma"><img src="https://opencollective.com/uptime-kuma/total/badge.svg?label=Open%20Collective%20Backers&color=brightgreen" /></a>
[![GitHub Sponsors](https://img.shields.io/github/sponsors/louislam?label=GitHub%20Sponsors)](https://github.com/sponsors/louislam) <a href="https://weblate.kuma.pet/projects/uptime-kuma/uptime-kuma/">
<img src="https://weblate.kuma.pet/widgets/uptime-kuma/-/svg-badge.svg" alt="Translation status" />
</a>

<div align="center" width="100%">
    <img src="./public/icon.svg" width="128" alt="" />
</div>

Uptime Kuma is an easy-to-use self-hosted monitoring tool.

<img src="https://user-images.githubusercontent.com/1336778/212262296-e6205815-ad62-488c-83ec-a5b0d0689f7c.jpg" width="700" alt="" />

### Light Mode:
More Screenshots:

<img src="https://uptime.kuma.pet/img/light.jpg" width="512" alt="" />

Status Page:

<img src="https://user-images.githubusercontent.com/1336778/134628766-a3fe0981-0926-4285-ab46-891a21c3e4cb.png" width="512" alt="" />

Settings Page:

<img src="https://louislam.net/uptimekuma/2.jpg" width="400" alt="" />

Telegram Notification Sample:

<img src="https://louislam.net/uptimekuma/3.jpg" width="400" alt="" />



## Live Demo

- Tokyo Demo Server: [https://demo.uptime.kuma.pet](https://demo.uptime.kuma.pet)

It is a temporary live demo, all data will be deleted after 10 minutes. Use the one that is closer to you, but I suggest that you should install and try it out for the best demo experience.

## Features

* Monitoring uptime for HTTP(s) / TCP / HTTP(s) Keyword / Ping / DNS Record / Push / Steam Game Server / Docker Containers
* Fancy, Reactive, Fast UI/UX
* Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP), and [90+ notification services, click here for the full list](https://github.com/louislam/uptime-kuma/tree/master/src/components/notifications)
* 20 second intervals
* [Multi Languages](https://github.com/louislam/uptime-kuma/tree/master/src/lang)
* Multiple status pages
* Map status pages to specific domains
* Ping chart
* Certificate info
* Proxy support
* 2FA support

## How to Install

## Deploy with Docker
### €⁠20 on [Hetzner Cloud](https://hetzner.cloud/?ref=eLtKhFK70n4h)

### Automatic Installs
```
https://github.com/WhateverItWorks/Watchtower
```

Run Uptime Kuma in production with docker-compose
```
git clone https://github.com/WhateverItWorks/my-uptime-kuma-docker-compose.git status
cd status
nano docker-compose.yml
docker-compose pull
docker-compose up -d
```
Uptime Kuma is now running on http://localhost:3001


Run Uptime Kuma in developer with docker-compose
```
git clone https://github.com/WhateverItWorks/my-uptime-kuma-docker-compose.git status
cd status
nano docker-compose.yml
docker-compose up -d --build
```
Uptime Kuma is now running on http://localhost:3001


## How to Update
```
docker-compose down
docker-compose pull
docker-compose up -d
```


## Security Audits:

- [Internet.nl](https://internet.nl/site/status.whateveritworks.org)
- [HSTS Preload](https://hstspreload.org/)
- [SSL Labs](https://www.ssllabs.com/ssltest/analyze.html?d=status.whateveritworks.org)
- [Security Headers](https://securityheaders.com/?q=status.whateveritworks.org&hide=on&followRedirects=on)
- [pagespeed](https://pagespeed.web.dev/)
- [webbkoll](https://webbkoll.dataskydd.net/en)
- [ImmuniWeb](https://www.immuniweb.com/ssl/status.whateveritworks.org)
- [Hardenize](https://www.hardenize.com/report/status.whateveritworks.org)
- [Mozilla.org](https://observatory.mozilla.org/)
- [report-uri.com](https://report-uri.com/home/tools)
- [check-your-website.server-daten.de](https://check-your-website.server-daten.de/?q=status.whateveritworks.org)
- [csp-evaluator.withgoogle.com](https://csp-evaluator.withgoogle.com/)
- [OpenWPM](https://github.com/openwpm/OpenWPM)
- [privacyscore.org](https://privacyscore.org/)

## 🗣️ Discussion / Ask for Help

⚠️ For any general or technical questions, please don't send me an email, as I am unable to provide support in that manner. I will not response if you asked such questions.

I recommend using Google, GitHub Issues, or Uptime Kuma's Subreddit for finding answers to your question. If you cannot find the information you need, feel free to ask:

- [GitHub Issues](https://github.com/louislam/uptime-kuma/issues)
- [Subreddit r/Uptime kuma](https://www.reddit.com/r/UptimeKuma/)

My Reddit account: [u/louislamlam](https://reddit.com/u/louislamlam).  
You can mention me if you ask a question on Reddit.


## Contribute

### Test Pull Requests

There are a lot of pull requests right now, but I don't have time to test them all.

If you want to help, you can check this:
https://github.com/louislam/uptime-kuma/wiki/Test-Pull-Requests

### Test Beta Version

Check out the latest beta release here: https://github.com/louislam/uptime-kuma/releases

### Bug Reports / Feature Requests
If you want to report a bug or request a new feature, feel free to open a [new issue](https://github.com/louislam/uptime-kuma/issues).

### Translations
If you want to translate Uptime Kuma into your language, please visit [Weblate Readme](https://github.com/louislam/uptime-kuma/blob/master/src/lang/README.md).

Feel free to correct my grammar in this README, source code, or wiki, as my mother language is not English and my grammar is not that great.

### Create Pull Requests
If you want to modify Uptime Kuma, please read this guide and follow the rules here: https://github.com/louislam/uptime-kuma/blob/master/CONTRIBUTING.md
