README
======

# Escapepod - Podcast Player for Android
<img src="https://raw.githubusercontent.com/y20k/escapepod/master/app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.png" width="192" />

**Version 1.0.0 ("Sag Alles Ab")**

Escapepod is a simple and lightweight app with a minimalistic approach for listening to podcasts, which may not be to everyone's liking. The app has only a single screen. Playback controls and a list of podcasts that shows the five most recent episodes each. Escapepod has no podcast discovery feature. It only offers a very simple search option and it opens RSS podcasts links when you tap them in a web browser.

Escapepod is free and open source. It is published under the [MIT open source license](https://opensource.org/licenses/MIT). Want to help? Please check out the notes in [CONTRIBUTE.md](https://github.com/y20k/escapepod/blob/master/CONTRIBUTE.md) first.

## Install Escapepod
You can install Escapepod via F-Froid and Google Play - or you can go and grab the latest APK on [GitHub](https://github.com/y20k/escapepod/releases).

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height="80">](https://f-droid.org/packages/org.y20k.escapepod/)

[<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" alt="Get it on Google Play" height="80">](https://play.google.com/store/apps/details?id=org.y20k.escapepod)

## Frequent Questions

### Does Escapepod have playback queue?
Escapepod has a simple up-next feature. Tap play on an episode while listening to another one. You will be be given the opportunity add it to the up-next slot.

### What are the default settings?
- Auto-update does not download files over cellular network
- Escapepod by default only keeps two episodes

### Escapepod keeps more than two episodes.
Escapepod tries to reduce the number of episodes it keeps. Here are the rules for that:

- Escapepod keeps the latest two episodes
- Episodes, that have been started, or that have been downloaded manually, are kept, too
- the maximum number of episodes available (and kept) is five

### Does Escapepod support OMPL?
You can import a podcast list using the [OPML](https://en.wikipedia.org/wiki/OPML) exchange format using the respective option in the app's Settings. The current podcast collection can be exported via Settings, too. Additionally Escapepod keeps an up-to-date OPML file in the folder `/Android/data/org.y20k.escapepod/files/collection/`.

### I cannot add podcast X.
Please report any podcast feeds, that are currently not working, using the GitHub Issue template [Feed Issue](https://github.com/y20k/escapepod/issues/new?assignees=&labels=feed+issue&template=feed-issue.md&title=%5BFeed%5D). Note: Escapepod does not support video podcasts.

### Where do the podcast search results come from?
Escapepod searches by default the [Podcastindex.org](https://podcastindex.org/) online database - or if you toggle the respective setting the [gpodder.net](https://gpodder.net/directory/) online database.


## Screenshots (v0.8)
[<img src="https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/01-lockscreen-active-v0.8-oneplus5.png" width="240">](https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/01-lockscreen-active-v0.8-oneplus5.png)
[<img src="https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/02-playback-v0.8-oneplus5.png" width="240">](https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/02-playback-v0.8-oneplus5.png)
[<img src="https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/03-large-player-sheet-v0.8-oneplus5.png" width="240">](https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/03-large-player-sheet-v0.8-oneplus5.png)

[<img src="https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/04-show_notes-v0.8-oneplus5.png" width="240">](https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/04-show_notes-v0.8-oneplus5.png)
[<img src="https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/05-podcast-details-v0.8-oneplus5.png" width="240">](https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/05-podcast-details-v0.8-oneplus5.png)
[<img src="https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/06-add-podcast-v0.8-oneplus5.png" width="240">](https://raw.githubusercontent.com/y20k/escapepod/master/metadata/en-US/phoneScreenshots/06-add-podcast-v0.8-oneplus5.png)
