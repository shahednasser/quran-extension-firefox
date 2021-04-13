# Quran In New Tab

![Quran In New Tab](https://github.com/shahednasser/quran-extension/blob/master/assets/icon-128.png?raw=true "Quran In New Tab")

Replace the new tab page with Quran verses and beautiful nature pictures. The verses and pictures are randomly generated hourly. You can choose to show or hide your top sites.

**You can find the chrome extension [here](https://github.com/shahednasser/quran-extension)**

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Quran In New Tab](#quran-in-new-tab)
	- [Download](#download)
	- [Hijri Dates](#hijri-dates)
	- [Recitations](#recitations)
	- [Translations](#translations)
	- [Athkar](#athkar)
	- [Prayer Times](#prayer-times)
	- [Credits](#credits)
	- [Development Note](#development-note)
	- [Issues](#issues)
	- [License](#license)

<!-- /TOC -->

## Download

Add the firefox extension [here](https://addons.mozilla.org/en-US/firefox/addon/quran-in-new-tab/).

## Hijri Dates

You can show today's Hijri date and holidays, if there are any.

## Recitations

You can play an audio of the recitation of the verse shown. You can choose from the following reciters:
- Mashary Rashid Alafasy
- Abdallah Basfar
- Abdurrahmaan As-Sudais
- Abdul Samad
and many more.

## Translations

You can turn on the translation for the verses. Some of the languages available for translations are:
- English
- German
- Spanish
- Indonesian
- Italian
and many more.


## Athkar

Starting from version 1.0, you can show randomly generated Athkar on your new tab as well.


## Prayer Times

Starting from version 2.1.2, you can now see prayer times and change their calculation method from the settings


## Credits

- All Quran verses, audios, translations, calendar and prayer times use the API of [Al Quran Cloud](https://alquran.cloud/)
- Icons from [Feather](https://feathericons.com/) and [Icon Scout](https://iconscout.com/)
- Logo from https://www.freeiconspng.com/img/8824

## Development Note

When adding this extension on firefox as a Temporary Add-on for development, you need to add the following in the `manifest.json`:

```json
"browser_specific_settings": {
  "gecko": {
    "id": "addon@example.com",
    "strict_min_version": "42.0"
  }
}
```

You can read more about this [here](https://blog.shahednasser.com/making-your-extension-compatible-with-both-chrome-and-firefox/#manifest)

## Issues

If you find any issues or bugs, please create a Github issue.


## License

Copyright © 2021 Shahed Nasser

Licensed under the [MIT License](https://github.com/shahednasser/quran-extension-firefox/blob/master/LICENSE).
