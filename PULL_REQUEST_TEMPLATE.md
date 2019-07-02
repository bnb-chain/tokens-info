In order to streamline the review of the contribution we ask you
to ensure the following steps have been taken:

1. Create a folder under `/tokens`, folder name is your token symbol in the `lowercase` format

2. Uploade your logo in your folder

- [ ] Filename in the `lowercase` format
- [ ] Image format: `png`
- [ ] Image size: `256 by 256 px`

3. Upload a json file for additional info. File name is your token symbol in the `lowercase` format

* `asset` must be your token's symbol
* `asserMap` must be your token's symbol without suffix
* `display`'s default value is `true`, which means the information will be available in the explorer

The following contacts are supported in `contact`:
* Twitter
* Facebook
* Reddit
* Instagram
* Medium
* Steemit
* Coinmarketcap
* Binance Info
* Youtube
* Telegram
* Discord
* Linkedin
* Github

> Note: you must use the right key name

Example:

```json
{
    "asset":"NOW-E68",
    "assetMap":"NOW",
    "officialSiteUrl":"https://changenow.io/",
    "contactEmail":"email@now.com",
    "display":true,
    "contact":{
        "Telegram":"https://t.me/NOWtoken_Bounty",
        "Reddit":"https://www.reddit.com/user/ChangeNow_io",
        "Medium":"https://medium.com/",
        "Youtube":"https://www.youtube.com/channel/UCpnkFY4kom0q3RJnhHiuMnw",
        "Twitter":"https://twitter.com/ChangeNOW_io",
        "Facebook":"https://www.facebook.com/ChangeNOW.io/"
    }
}

```