<!-- Banner Image -->
<p align="center">
    <img width="460" height="300" src="(https://cdn.jsdelivr.net/gh/editionsojib/al-quran_max-api/quran.jpg)" alt="Quran API Banner">
</p>

<h1 align="center">📖 Quran API</h1>

<p align="center">
    <a href="https://www.jsdelivr.com/package/gh/fawazahmed0/quran-api">
        <img src="https://data.jsdelivr.com/v1/package/gh/fawazahmed0/quran-api/badge" alt="jsDelivr">
    </a>
    <a href="https://www.jsdelivr.com/package/gh/fawazahmed0/quran-api">
        <img src="https://data.jsdelivr.com/v1/package/gh/fawazahmed0/quran-api/badge/rank" alt="jsDelivr Rank">
    </a>
</p>

<p align="center"><b>In the name of God, who has guided me to do this work</b></p>

---

<p align="center">
    <b>🌍 Free, Fast, and Open Quran API</b><br>
    <i>Access the Quran and 440+ translations in 90+ languages, structured for developers.</i>
</p>

---

## 🚀 Features

- **Free & Blazing Fast** responses
- **No Rate Limits**
- **90+ Languages** & **440+ Translations** (including Latin/Roman scripts)
- **RESTful API** structure for easy integration

---

## 🌐 URL Structure

```
https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@{apiVersion}/{endpoint}
```

### Supported Formats

- `{endpoint}.json` (prettified)
- `{endpoint}.min.json` (minified)

> **Tip:** Always implement a fallback between `.json` and `.min.json` formats. [Learn more.](https://github.com/fawazahmed0/quran-api/issues/27)

---

## 📚 Endpoints Overview

| Endpoint | Description |
|----------|-------------|
| `/editions` | List all available editions ([json](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions.json) / [min.json](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions.min.json)) |
| `/editions/{editionName}` | Get full Quran/translation ([example](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions/ben-muhiuddinkhan.json)) |
| `/editions/{editionName}-la` | Get Latin (Roman) script version |
| `/editions/{editionName}-lad` | Latin script with diacritics |
| `/editions/{editionName}/{ChapterNo}` | Get a full chapter ([example](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions/ben-muhiuddinkhan-la/5.json)) |
| `/editions/{editionName}/{ChapterNo}/{VerseNo}` | Get a specific verse ([example](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions/ben-muhiuddinkhan-lad/5/10.json)) |
| `/editions/{editionName}/juzs/{juzNo}` | Get a specific Juz ([example](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions/ben-muhiuddinkhan-lad/juzs/3.json)) |
| `/info` | Quran metadata ([json](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/info.json)) |
| `/fonts` | List available Arabic fonts ([json](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/fonts.json)) |

<details>
<summary>Other endpoints</summary>

- `/editions/{editionName}/rukus/{rukuNo}`
- `/editions/{editionName}/pages/{pageNo}`
- `/editions/{editionName}/manzils/{manzilNo}`
- `/editions/{editionName}/maqras/{maqraNo}`

</details>

---

## 🖋️ Displaying Text

- Use [Arabic Fonts](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/fonts.json) for Quran text. If you see missing characters, try fonts with the `-full` suffix ([details](https://github.com/fawazahmed0/quran-api/blob/1/fontfull.md)).
- For translations, use [Google Noto Fonts](https://www.google.com/get/noto/) to ensure proper display for all languages.

---

## 🌏 Languages Available

- **98 languages** and **440+ translations** ([list](https://github.com/fawazahmed0/quran-api/blob/1/Translations.md))
- Some translations are [OCRed](https://github.com/fawazahmed0/quran-api/blob/1/Translations.md#ocred) and may contain mistakes. Please [report issues](https://github.com/fawazahmed0/quran-api/issues/new).

---

## 🤝 Contribution

Your help keeps this project alive!  
- Found an issue? [Let us know](https://github.com/fawazahmed0/quran-api/issues/new).
- Add new translations: [Share here](https://github.com/fawazahmed0/quran-api/issues/new) or read the [contribution guide](https://github.com/fawazahmed0/quran-api/blob/1/CONTRIBUTING.md).

---

## ⬇️ Download

- [Download resources](https://github.com/fawazahmed0/quran-api/blob/1/download.md)

---

## 🛡️ Authenticity

- No controversial authors included (e.g., Rashad Khalifa).
- Ahmaddiya translations are not included due to doctrinal differences.
- If you find questionable translations, [report here](https://github.com/fawazahmed0/quran-api/issues/new).

---

## 🧑‍💻 Demo Projects

- [Quran](https://fawazahmed0.github.io/quran)
- [Quran Recitation Videos](https://github.com/fawazahmed0/quran-videos)
- [Quran Verse Detection](https://github.com/fawazahmed0/quran-verse-detection)
- [Quran Hadith Search Engine](https://fawazahmed0.github.io/quran-hadith-search/)
- [Random Verse Generator](https://rrakibul.github.io/quran-quotes/)

---

## 🔗 Other APIs

- [Hadith API](https://github.com/fawazahmed0/hadith-api#readme)
- [Tafsir API](https://github.com/spa5k/tafsir_api#readme)

---

## ⭐ Share & Support

If you find this API useful, please [share it](https://fawazahmed0.github.io/donate.html?mymsg=Thanks%20for%20using%20this%20API%2C%20I%20am%20Fawaz%20Ahmed%20(fawazahmed0)%20developer%20of%20this%20repo.%20I%20made%20this%20API%2C%20for%20three%20main%20reasons%3A%3Cbr%3E%3Cbr%3E%0A1.%20To%20spread%20the%20word%20of%20God%20around%20the%20world.%3Cbr%3E%3Cbr%3E%0A2.%20So%20the%20developers%20don't%20have%20to%20start%20from%20scratch.%3Cbr%3E%3Cbr%3E%0A3.%20To%20make%20a%20free%20unlimited%20service%2C%20which%20doesn't%20depend%20on%20any%20donation%20or%20any%20single%20person%20for%20it's%20future%20existence.%3Cbr%3EMy%20death%20won't%20have%20any%20effect%20on%20it%20by%20God's%20grace%2C%20as%20this%20API%20depends%20on%20the%20Free%20Open%20Source%20services%2C%20which%20todays%20internet%20infrastructure%20depends%20upon.%0A%3Cbr%3E%3Cbr%3E%3Cbr%3E%0AIf%20you%20like%20to%20be%20part%20of%20this%20ongoing%20charity%2C%20then%20please%20do%20share%20this%20API%20with%20your%20fellow%20mates&sharelink=https%3A%2F%2Fgithub.com%2Ffawazahmed0%2Fquran-api&smallsharetext=Free%20Quran%20API%20Service&largesharetext=Quran%20API%20Service%20with%2090%2B%20different%20languages%20and%20400%2B%20translations%20for%20Free&sharebtnmsg=Share%20the%20Quran%20API%20Service&nodonatebtn=yes) and star the repo!

---

## 💝 Donation

I do not accept donations for myself. Please support the original authors and Islamic/dawah publishers who made these translations possible.  
See [Editions](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions.json) and [References](https://github.com/fawazahmed0/quran-api/blob/1/References.md) for details.

---

## 📖 References

- All open source projects and dawah/Islamic organizations
- [Editions](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions.json)
- [References](https://github.com/fawazahmed0/quran-api/blob/1/References.md)

---

<p align="center">
    <a href="https://github.com/fawazahmed0/quran-api/edit/1/README.md">:pencil2: <b>Improve this page</b></a>
</p>
