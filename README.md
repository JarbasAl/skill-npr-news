# <img src='https://raw.githack.com/FortAwesome/Font-Awesome/master/svgs/solid/newspaper.svg' card_color='#000000' width='50' height='50' style='vertical-align:bottom'/> Latest news
Listen to the latest news report from your favorite broadcast

# NOTE: this fork includes catalan news, once the official mycroft skill is updated this repo will be deleted!

Due to a backend issue the PR for this skill has been blocked in mycroft repositories, it also includes some bug fixes, read more [here](https://github.com/MycroftAI/skill-npr-news/pull/102)

If you are using this skill, you have to [disable the official skill](https://mycroft-ai.gitbook.io/docs/skill-development/faq#how-do-i-disable-a-skill) because they are incompatible

To play https streams properly you also need to install vlc

```bash
sudo apt-get install vlc
```

and make it the default it in your .conf

```json
  "Audio": {
    "backends": {
      "local": {
        "active": false
      },
      "vlc": {
        "active": true
      }
    },
    "default-backend": "vlc"
  },
```





## About
Play the latest news from an RSS audio feed. Your device location will be used to provide a local feed from your country if available. Otherwise, the National Public Radio (NPR)
Hourly News will be used. You can also choose your own default or add a custom audio feed at: [home.mycroft.ai](https://home.mycroft.ai/#/skill).

Supported stations include:

- [ES] RNE Radio Nacional de España
- [ES] CCMA Catalunya Informació
- [PT] TSF Rádio Notícias
- Associated Press (AP) Hourly Radio News
- [AU] ABC News Australia
- [BE] VRT Nieuws
- [CA] CBC News
- [DE] DLF
- [DE] WDR
- [FI] YLE
- [SE] Ekot
- [UK] BBC News
- [US] Fox News
- [US] NPR News Now
- [US] PBS NewsHour

## Examples
* "Play the news"
* "Play the BBC news"
* "Tell me the news"
* "What's the news?"
* "Restart news"

## Credits
Mycroft AI (@MycroftAI)

## Category
**Daily**
Information

## Tags
#news
#headlines
