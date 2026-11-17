# Church of Love web releases

[Build 109 source ZIP](Church-of-Love-Source-109.zip) · [Source history through build 109](Church-of-Love-History-through-109.bundle)

Dates use Vietnam time (UTC+7). The first seven entries use hosting release numbers. Each source revision can be checked out from the bundle.

| Source date | Version | Source revision | What changed |
| --- | --- | --- | --- |
| 2026-11-17 | Build 109 | `d93c631` | Added page language, descriptive title, search and sharing metadata, canonical URL, robots.txt and sitemap. Preserved build 108 icons and the chapel experience. |
| 2026-11-17 | Build 108 | `e82ce5c` | Existing hosted revision recovered before SEO work; includes favicon and touch icons. |
| 2026-11-16 | Build 106 | `403de82` | Made “You can confess now.” a button that enters the private room directly. Lighting the candle alone leaves the visitor at the candles. |
| 2026-11-16 | Build 105 | `715f483` | Displayed the confirmation “You can confess now.” after lighting a chapel candle. |
| 2026-11-16 | Build 104 | `767a35f` | Added opt-in Google Tag Manager and Microsoft Clarity with masked page text and analytics preferences. |
| 2026-11-16 | Build 103 | `6a921af` | Restored recent text context in the first message after reconnecting and suppressed duplicate greetings. |
| 2026-11-16 | Build 102 | `45c81b7` | Added tester text-chat pause, resume and explicit clearing within a tab. |
| 2026-11-16 | Build 101 | `5f1898b` | Separated the lit-candle status from the action to open Father and updated script loading. |
| 2026-11-16 | Build 100 | `bbd736d` | Improved offline messaging and handling of same-day candle storage. |
| 2026-11-16 | Build 99 | `72a2a6d` | Removed Next reflection and kept Talk to Father in the private room. |
| 2026-11-16 | Release 7 | `b8e6e39` | Renamed the chapel Church of Love and included the chapel candle gate for Father. |
| 2026-11-16 | Release 6 | `f603fc0` | Updated microphone readiness, connection timeouts and cancellation during connection. |
| 2026-11-16 | Release 5 | `fe61261` | Added live Father Gabriel Speak and Text controls and their browser audio assets. |
| 2026-11-16 | Release 4 | `7100974` | Updated garden drag controls and kept Candle, Rosary and Confession available in the bottom navigation. |
| 2026-11-16 | Release 3 | `3d1442f` | Rebuilt the garden entrance façade and corrected its rose window. |
| 2026-11-16 | Release 2 | `464b33d` | Switched to Pew Chapel 3D and shipped the Three.js renderer with the site. |
| 2026-11-16 | Release 1 | `5c9a165` | First hosted Quiet Garden scene. |

## Run locally

Extract the latest ZIP. From its church-of-love folder run `python3 -m http.server 8000 --directory dist` and open http://localhost:8000.

To inspect earlier releases, run `git clone Church-of-Love-History-through-106.bundle church-history`, then use `git -C church-history checkout <revision>`.

For each future published version, add its source and a dated entry with the build number, source revision, and user-facing changes.
