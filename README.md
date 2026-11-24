# The Forge for Kodi

The Forge is a Kodi 21 (Omega) skin by Merlin88 (Foundry 88 Labs), plus a small helper add-on that sets everything up for you. One look, built around Fen Light, Trakt and a NAS library.

What The Forge adds on top of its Arctic Horizon base:

- A forged navigation bar with search on the left and the power menu on the right.
- Expanding poster and landscape tiles on the home rows, with Play, Trailer and Info on each.
- Forge Tiles and Forge Wall views for movies and shows, and a Forge Series view for seasons and episodes.
- A search screen that keeps the navigation bar and shows results as expanding tiles.
- Two full-screen spotlight styles: Forge Full Screen Card and Forge Fullscreen Poster.
- A reskinned playback OSD.
- Movie sets: rows of sets, a release-timeline view for each set, and an offer to play the next movie when one ends.
- A helper screen that shows installed and available versions, updates everything in one press, and can roll back.

Layouts not yet replaced still come from Arctic Horizon.

## Install

1. In Kodi, open Settings, System, Add-ons and turn on **Unknown sources**.
2. Download `script.forge.helper-0.8.3.zip` from this repository.
3. In Kodi, open Add-ons, **Install from zip file**, and pick that zip.
4. A setup wizard starts on its own. It installs the skin and the add-ons it needs (including YouTube for trailers), signs you in to Trakt and Premiumize, and configures playback.

The wizard can be reopened any time from Add-ons, Forge Helper, Run setup wizard.

## What is in here

- `repo/` is a Kodi add-on repository. The wizard installs it so the skin and helper update themselves.
- `script.forge.helper-0.8.3.zip` is the one file you install by hand.

No accounts or personal settings are included. Everyone signs in with their own.

## Trakt

The Forge uses Trakt but is not endorsed or certified by Trakt.

Signing in to Trakt is optional. It is used to show what you have watched, your lists and your progress, and to record what you watch from this device. See the [privacy policy](PRIVACY.md) for exactly what is stored and where.

## Privacy

The Forge has no servers and collects nothing about you. The full statement is in [PRIVACY.md](PRIVACY.md).

## Credits and licence

The skin is built on Chameleon, a fork of **Arctic Horizon 2** by jurialmunkey (2.1 by DeFiNiek), and is shared under the same licence, Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (see `LICENSE-skin.txt`). It may not be used commercially. The helper add-on is GPL-3.0-or-later.

The Forge does not include or host any media. Third-party add-ons are downloaded from their own sources, with one exception: Fen Light 2.0.07 by Tikipeter is mirrored here unmodified, because its original download source no longer exists.
