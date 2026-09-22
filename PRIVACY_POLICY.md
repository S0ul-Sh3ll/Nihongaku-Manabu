# Privacy Policy — Nihongaku Manabu

**Last updated:** 22 September 2026

Nihongaku Manabu ("the app") is an offline Android music and video player that
overlays Japanese lyrics with furigana, per‑word meanings and full‑sentence
translations. This policy explains what the app does and does not do with your
information.

**Contact:** rishabhdahiya.work@gmail.com

---

## Summary

- The app is **offline‑first**. Your music, videos and lyrics stay **on your device**.
- We (the developer) **do not collect, store, or sell any personal information**, and the
  app has **no user accounts, sign‑in, or analytics SDK**.
- The only data leaving your device is: (1) a **song title/artist you choose to look up**
  when you tap *Get lyrics* (sent to a public lyrics service), and (2) data handled by
  **Google AdMob** to show the in‑app banner ad.
- The microphone permission is used **only** for the on‑screen music visualizer and
  audio is **never recorded, saved, or transmitted**.

---

## Information the app accesses on your device

- **Your media files (audio/video).** You explicitly pick songs, videos or a folder
  through Android's system file picker. The app reads these files to play them and to
  read basic tags (title, artist, genre, duration, embedded artwork). **These files are
  never uploaded anywhere.**
- **Lyrics/subtitles you add.** Lyric or subtitle files you attach, and any lyrics you
  paste, are stored **locally** in the app's private storage.
- **App data.** Your library list, the media‑to‑lyrics pairings, timing adjustments and
  settings are stored **locally on your device** (in the app's private database and files).

This on‑device data is not transmitted to the developer or to any server.

## Information sent off your device

The app uses the internet only for the following:

1. **Optional lyrics lookup (LRCLIB).** When you tap **"Get lyrics"**, the app sends the
   current track's **title and artist** to the free, public lyrics database
   [LRCLIB](https://lrclib.net) to find matching lyrics. No account, device identifier, or
   personal data is sent. If you never tap *Get lyrics*, no such request is made.
2. **"Find on web".** Tapping this opens **your own browser** to a web search for the
   song. From that point your browser and search engine apply their own privacy policies.
3. **Advertising (Google AdMob).** The app displays a banner advertisement served by
   **Google AdMob**. AdMob and Google may collect and process information such as your
   **advertising identifier, IP address, general (coarse) location, and app‑interaction
   data** to select, deliver, cap, and measure ads. This processing is governed by
   Google's policies:
   - How Google uses information from apps that use its services:
     <https://policies.google.com/technologies/partner-sites>
   - Google Privacy Policy: <https://policies.google.com/privacy>
   - You can limit ad personalization in **Android → Settings → Privacy → Ads**
     (reset or delete your advertising ID).

On‑device Japanese analysis (readings, per‑word meanings) and English translation are
performed **entirely on your device** (Sudachi, JMdict and Google ML Kit's offline
translation models). The text of your lyrics is **not sent to any server** for
translation.

## Permissions and why they are used

| Permission | Why it is used |
|---|---|
| **Internet / Network state** | Fetch lyrics from LRCLIB (only when you ask) and serve the AdMob banner. |
| **Microphone (RECORD_AUDIO)** | Powers the optional on‑screen **audio visualizer**, which reacts to the currently playing sound in real time. Audio is processed live and is **never recorded, stored, or transmitted**. If the permission is denied, the visualizer falls back to a time‑based animation. |
| **Foreground service / media playback** | Keep music playing and show media controls in the notification while the app is in the background. |
| **Notifications (POST_NOTIFICATIONS)** | Show the playback controls notification. |

The app requests access to the specific media files or folder you choose through the
system picker; it does not request broad access to all files on your device.

## Third‑party services

- **Google AdMob / Google Play Services** — advertising and core Google services.
  See Google's policies linked above.
- **LRCLIB (lrclib.net)** — public, key‑less lyrics database used only when you tap
  *Get lyrics*.

## Children's privacy

The app is not directed to children under 13, and we do not knowingly collect personal
information from children. Because the app shows advertising, we recommend it for a
general audience.

## Data retention and deletion

- All app data lives on your device. **Uninstalling the app deletes all of it.**
- You can remove individual tracks or clear paired lyrics from within the app at any time.
- The developer holds no personal data about you, so there is nothing for us to delete on
  a server.

## Security

Your library, lyrics and settings remain in the app's private on‑device storage. Because
the app does not upload your files or maintain accounts, the main privacy consideration is
the advertising described above.

## Changes to this policy

We may update this policy as the app evolves. Material changes will be reflected here with
a new "Last updated" date. Continued use of the app after an update constitutes acceptance
of the revised policy.

## Contact

Questions about this policy or the app's data practices:
**rishabhdahiya.work@gmail.com**
