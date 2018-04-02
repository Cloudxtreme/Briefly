<p align="center">
  <a href="" rel="noopener">
 <img width=300px src="./assets/Briefly.png" alt="Briefly-logo"></a>
</p>

<h3 align="center">Source based news network</h3>

<div align="center">

[![Gitter](https://img.shields.io/gitter/room/bri3fly/bri3fly.svg)](https://gitter.im/bri3fly/Lobby)
[![Website cv.lbesson.qc.to](https://img.shields.io/website-up-down-green-red/http/cv.lbesson.qc.to.svg)](https://github.com/inishchith/Briefly-web/tree/master)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
<br>
[![HitCount](http://hits.dwyl.io/inishchith/Briefly.svg)](http://hits.dwyl.io/inishchith/Briefly)


</div>

------------------------------------------

>There are no personalized , summary based  news resources available in the current scenario . We've built a `Source based news network` where the user has the control over the feed from any given `source` in any given `language` .


<div align="center">
&#10077; It's the user who decides what he needs &#10078;  -  <a href ="https://github.com/shivam1708"> cheetAh </a>
</div>


------------------------------------------
### Features

- `Subscriptions` for a news source
- `Bookmark` an article
- `Summarize` an source article or a url
- Browse across ~ 255 preffered source listed [here](./App/sources.csv)
- Featured Article as per all user reaction ( Also an Add-Ons )
- `Night-Mode` for better readiblity
- Subscribe to your favorite source using `chatbot` and read it on your own comfort from the `web-app`

<div align="center">

<h3 > Briefly As Web-App  </h3>
<br>
<p align="center">
<img src ="./assets/briefly-web.gif" width = 500px>
</p>

<h3><a href="https://www.facebook.com/Briefly-350014818823728/">  Briefly On Messenger   </a></h3>
<br>
<img src="./assets/sync-sub.gif" width=245px>
<img src="./assets/show-news.gif" width=245px>

</div>

------------------------------------------

### Add-Ons

- [ ] Offline news feed for subscriptions
- [ ] Daily Mail ( yet to be integrated with template )
- [ ] Add More

------------------------------------------
### File Structure


#### ChatBot

- `App` : Source code for chatbot
- `Scrappers` : Scrapper for maintaining inital news distribution across web-app and chatbot using firebase . Deployment of this would result in frequent update the news

#### Web-App

- Repository [here](https://github.com/inishchith/Briefly-web/tree/master)

------------------------------------------
### Installation

* Install dependencies
```sh
        $ pip3 install -r requirements.txt
```

* Edit [config.py](https://github.com/inishchith/Briefly/blob/master/App/config.py)

* Add :fire:firebase project credentials here [1](https://github.com/inishchith/Briefly/blob/master/App/subscribe.py) [2](https://github.com/inishchith/Briefly-web/blob/master/mhack/basic_app/subscribe.py)

------------------------------------------
### Contributing

 We're are open to `enhancements` & `bug-fixes` :smile: Also do have a look [here](./CONTRIBUTING.md)

### Note

- This project was done under `24 hours with minimal pre-preparation`
- Extended capabilities of scraper to `Indian Languages` ( Hindi & Marathi supported as of now)

------------------------------------------
### Contributors

- [@shivam1708](https://github.com/nurdtechie98)
- [@nurdtechie98](https://github.com/shivam1708)
- [@freelancer-98](https://github.com/Freelancer-98)
- [@inishchith](https://github.com/inishchith)

------------------------------------------
### Recognition

This repository / project was a part of [@MumbaiHackathon](https://github.com/MumbaiHackathon/) 2018

<div align="center">
<img src="./assets/winners.png" width=500px height=350px alt="winners 2018">
</div>
