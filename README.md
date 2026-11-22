# chrome-internal-urls
All of the chrome internal URLs
# Chrome Internal URLs (`chrome://`) Reference

A curated, categorized directory of Google Chrome's built-in internal pages (`chrome://` URLs) for settings, diagnostics, experiments, and debugging.

> **Tip:** To see every internal URL supported by your exact browser version and OS, type `chrome://chrome-urls` (or `chrome://about`) into your Chrome address bar.

## Everyday & Management

| URL | Description |
| :--- | :--- |
| `chrome://settings` | Main browser settings and preferences |
| `chrome://bookmarks` | Bookmark Manager |
| `chrome://history` | Browsing history |
| `chrome://downloads` | Downloads Manager |
| `chrome://extensions` | Manage installed extensions and developer mode |
| `chrome://apps` | Installed Chrome web apps |
| `chrome://newtab` | Default New Tab page |
| `chrome://dino` | Offline T-Rex runner game |

## Experiments & System Info

| URL | Description |
| :--- | :--- |
| `chrome://flags` | Enable or disable experimental features *(use with caution)* |
| `chrome://version` | Browser version, user agent, profile paths, and command-line flags |
| `chrome://components` | View and manually update internal browser components (e.g., Widevine, CRLSet) |
| `chrome://management` | Check if the browser is managed by an organization or enterprise policy |
| `chrome://policy` | View active administrative policies |
| `chrome://system` | Detailed system diagnostic data |

## Network, Performance & Debugging

| URL | Description |
| :--- | :--- |
| `chrome://net-internals` | Inspect network state, DNS cache (`#dns`), and sockets (`#sockets`) |
| `chrome://gpu` | Graphics hardware details and hardware acceleration status |
| `chrome://discards` | View open tabs, memory usage, and tab discard status |
| `chrome://crashes` | View recent crash reports and IDs |
| `chrome://inspect` | Inspect connected USB devices, pages, and service workers |
| `chrome://media-internals` | Debug active audio and video playback |
| `chrome://webrtc-internals` | Inspect WebRTC peer connections and stats |

## Developer Crash / Test URLs
*Warning: Navigating to these URLs will intentionally freeze or crash a tab or browser process.*
* `chrome://crash` – Simulates a renderer crash in the current tab
* `chrome://kill` – Terminates the current tab's process
* `chrome://hang` – Freezes the current tab's UI thread
* `chrome://gpucrash` – Simulates a GPU process crash
