# sovo. App Store edition — Privacy Policy

Last updated: 18 November 2026

sovo. is a personal audiobook player for iPhone, iPad and Mac. This policy covers the native App Store edition. The separate desktop catalogue/torrent application has its own policy.

## Your library

Audio, book metadata, bookmarks, listening history and playback positions are stored in the app's local library. The You page calculates shelves, listening time and streaks locally; an optional reader name stays on this device. sovo. does not operate a developer-hosted account or audio-upload service. Imported original files are retained unless you choose to remove them through the app or your file provider.

## Optional iCloud

When you enable iCloud library sync, library files and metadata are sent to your private Apple iCloud app container. Playback position also uses Apple's iCloud key-value storage. Apple processes this information under its own privacy policy and your iCloud account settings. Sync availability depends on your account, storage and network. When Goodreads shelf sync is enabled, the selected Goodreads profile identifier, cached book/shelf records and sync timestamps are also stored in your private iCloud container. Goodreads passwords, cookies, website sessions and media-server credentials are not uploaded to iCloud. The Goodreads sync switch is per device; disconnecting locally turns that device’s Goodreads sync off and does not delete other devices’ copies.

## Automatic metadata lookup

Imports first read embedded tags and artwork. Automatic matching sends book title and author text to Apple Books Search and, when needed, Open Library, and downloads matched cover images. A matching public Apple Books edition page can provide narrator, publisher, language and release-year credits; title/author and running time are checked before applying edition-specific credits. Audio is never uploaded for metadata. Lookup requires a network connection; unavailable or uncertain matches leave existing details intact. Missing covers are retried automatically, at most daily per book. You can still edit book information yourself.

## Public author and narrator profiles

Opening author/narrator browsing can send a person’s name to Wikipedia and Wikimedia Commons to retrieve a matching biography, portrait and image-license credits. These services receive normal connection information such as IP address. Profiles are cached locally in memory; no audio or Goodreads credentials are sent. Unavailable or ambiguous profiles keep a placeholder. Source and license links accompany retrieved biographies and portraits.

## Goodreads

Connecting Goodreads opens Goodreads in an app-specific website session. Sign-in information is submitted to Goodreads or its sign-in provider, and website cookies remain in the app's WebKit storage. Goodreads and any pages opened there are governed by their respective privacy policies. The app stores your selected profile identifier and a cache of your reading shelves, optionally synchronized through your private iCloud; it does not provide a developer-hosted copy of your account. You may disconnect Goodreads and remove the cached connection in Settings. A CSV import is available instead of website sign-in.

The embedded session blocks third-party webpage resources except Goodreads/Amazon provider assets and Google CAPTCHA resources needed for authentication. Website JavaScript is enabled for authentication and explicitly opened Goodreads book/review/shelf pages, and disabled during background shelf refresh; the app reads shelf HTML with its own code. Changes made through an interactive Goodreads page are submitted directly to Goodreads. If these controls cannot initialize, the app does not load Goodreads pages and offers retry or CSV import. No advertising SDK, IDFA access or developer-operated cross-app tracking is included.

Goodreads/Amazon may retain account information, identifiers, approximate network location and website activity for their account, security, personalization and analytics purposes. The Store privacy label conservatively includes this optional provider data. These practices are governed by the [Goodreads Privacy Policy](https://www.goodreads.com/about/privacy) and Amazon's linked notice. The resource controls do not erase information already held by a provider or promise to control its server-side processing.

## Your own media server

Audiobookshelf and Jellyfin connections send authentication and download requests directly to the HTTPS server you specify. Server access tokens are stored in the device Keychain, not in configuration JSON or iCloud. Passwords are used for sign-in and are not saved by sovo. Removing a server removes its saved token. The server operator can see the requests you send to that server.

## Browser transfer and file downloads

A browser transfer starts only when you enable a temporary session. It uses local HTTP and a secret link on a trusted network; close the transfer screen to stop it. Do not use this feature on an untrusted network. Direct file downloads use HTTPS. The optional free-classic entry downloads a LibriVox recording from Internet Archive when you choose to add it; the source page, recording credits and regional copyright notice are shown before download. Download hosts and your network provider may process connection information under their own policies.

## Widgets and share extension

The widget and share extension use a private App Group shared only by sovo.'s signed app components. Widget snapshots contain the current and recent book titles, authors, progress and playback state. Shared audio files are staged there until the main app imports them.

## AirPods sleep pause

The app handles standard Apple media pause commands and offers setup instructions for supported AirPods’ Pause Media While Falling Asleep feature. Detection and the setting are controlled by Apple. sovo. does not read heart rate, request HealthKit access, diagnose sleep, record workouts or upload health information for this feature. The ordinary sleep timer remains available without AirPods.

## App Store update checks

The app can request public version information for its App Store listing from Apple, using the listing ID, bundle ID and storefront country. No audiobook, shelf, account token or listening history is sent. Apple receives the request and network information under its policies. Installation and automatic updates remain controlled by the App Store.

## Analytics and advertising

sovo. does not include advertising, a developer analytics service or cross-app tracking SDKs. Apple may provide operating-system and App Store diagnostics according to your device settings. External websites, Apple services and user-selected servers may apply their own logging and privacy practices.

## Your choices and contact

You can disable optional network integrations and iCloud, remove books and connections, and delete the app's data through your device settings. Removing local data does not necessarily remove copies retained by iCloud, external servers, your original Files library or backups. For privacy questions or support, open an issue at https://github.com/Somamill/sovo/issues. Do not post passwords, tokens or private files in a public issue.
