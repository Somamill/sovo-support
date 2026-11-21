# sovo.

Support for **sovo.**, the native iPhone, iPad and Mac audiobook player.

sovo. plays your own DRM-free audiobooks. Import a file, folder or ZIP, then keep your place with chapters, bookmarks, playback speed and a sleep timer. There is no sovo. account, subscription, in-app purchase or supplied audiobook catalogue. 

## Try a book without an account

[Download the two-minute Alice’s Adventures in Wonderland excerpt](https://raw.githubusercontent.com/Somamill/sovo-support/main/samples/alice-preview.m4b). This LibriVox sample is public domain in the United States. [See recording credits](samples/AUDIO-CREDITS.md).

1. Open **Library → + → Download a file**, paste the sample URL and select **Download**. You can also save the file to Files and select **Import audio files**.
2. Tap the imported book to open the player and start listening.
3. Tap **Done** to return to the library. The mini-player keeps the book and its playback controls available.

## Metadata and genres

Every imported record has a title, an author label and a genre label. Embedded tags are used first; confident matches from Apple Books and Open Library fill missing details and genres. Unknown bibliographic facts are not invented: unmatched books show Unknown author or Uncategorized and are retried automatically. Titles and genre can also be corrected in Book details. Initialled author names such as JRR Tolkien are matched consistently with punctuated initials.

Use **Library → Genre** to view automatic shelves such as Fantasy, Mystery & Crime or Nonfiction. Genre organization refers to the same library books; it does not require extra audio copies. A converted M4B includes its known genre tag.

## AirPods automatic sleep pause

With supported AirPods connected, enable **Pause Media While Falling Asleep** in the device’s AirPods settings (look under Audio & Routing if necessary). sovo. handles Apple’s normal pause command and saves your position. The setup guide is in **Settings → Sleep** and the player’s sleep-timer menu.

Apple controls detection, supported hardware and the setting. sovo. cannot enable or inspect the switch, and no live heart-rate tracking is used. Detection can be delayed or unavailable; choose a timer or End of chapter for a predictable stop.

Official instructions: [AirPods settings and sleep pause](https://support.apple.com/108764). [Heart-rate monitoring on AirPods Pro 3](https://support.apple.com/guide/airpods/track-heart-rate-workouts-airpods-pro-3-dev1b40fb47d/27/web/27) is a separate workout feature.

## You

The **You** tab separates Next, Listening and Finished books and shows real listening minutes, a seven-day chart and your current streak. Time and streaks are recorded on this device; book progress follows your iCloud library. Set an optional reader name in Settings.

## Optional connections

- **Goodreads:** connect in the app's own web session, independent of Safari. Reading shelves are read-only; sovo. does not write ratings or reading progress to Goodreads. A Goodreads CSV can also be imported as a snapshot. [Download a fictional shelf demonstration](https://raw.githubusercontent.com/Somamill/sovo-support/main/samples/goodreads-demo.csv), then open Settings → Goodreads → Other ways to bring your shelves → Import Goodreads CSV. The demonstration is not a live account connection.
- **iCloud:** uses your Apple account for optional library/progress synchronization. Enable **Sync Goodreads shelves with iCloud** to share your Goodreads profile and saved shelves between devices. Cookies and sign-in stay on each device; a new sign-in may be needed for live refresh. This is not two-way writing of progress or ratings to Goodreads. Give uploads time to finish before opening another device. Download books before going offline.
- **Audiobookshelf or Jellyfin:** add your own server and credentials in Settings → Media servers. These services are not required for local playback.
- **Browser transfer:** starts a temporary local-network upload session. Keep its secret link private and close the transfer screen when finished.

Disconnecting Goodreads turns off Goodreads sync on this device and removes its local connection and website data, while other devices and existing iCloud copies are retained; it does not delete your external Goodreads or Amazon account. Manage external accounts with the relevant provider. There is no separate sovo. account to delete.

## Help and privacy

For an import problem, check that the file contains supported, unencrypted audio. HTTPS downloads need a direct file URL rather than a website or login page. Metadata and covers are automatic, using embedded tags, Apple Books and Open Library. Missing covers are retried daily. Uncertain matches are skipped; touch and hold a book to edit its details. For a server connection problem, confirm the server is reachable and its certificate is valid.

[Report an issue](https://github.com/Somamill/sovo-support/issues/new) with your device, OS, app version and steps to reproduce. Do not include passwords, private server tokens, personal audiobook files or account data in a public issue.

[Privacy policy](PRIVACY.md) · [Review guide](REVIEW.md) · [Audio sample credits](samples/AUDIO-CREDITS.md)


## Localized quick guides

- [العربية](support/ar-SA.md)
- [বাংলা](support/bn-BD.md)
- [Deutsch](support/de-DE.md)
- [Español](support/es-ES.md)
- [Français](support/fr-FR.md)
- [हिन्दी](support/hi.md)
- [Bahasa Indonesia](support/id.md)
- [日本語](support/ja.md)
- [Português (Brasil)](support/pt-BR.md)
- [Русский](support/ru.md)
- [简体中文](support/zh-Hans.md)

Questions, ideas, or spotted a bug? [Email Max](mailto:max@miller-max.com). Feedback is always welcome.
