## Thunderblur

### A blurred CSS theme for Thunderbird

| Inbox |
| --- |
| ![screenshot](images/inbox.png) |

| Calendar |
| --- |
| ![screenshot](images/calendar.png) |

| Compose Window |
| --- |
| ![screenshot](images/compose.png) |


## How to

1. Open the Thunderbird Menu located on the top-right corner with a humburger menu(three horizontal lines).
2. Select `Preferences`, then `Preferences` again.
3. Go to `Advanced`, find the `Config Editor` button then press it.
4. A dialog will warn you, but ignore it, ~~just do it~~ press the `I accept the risk!` button.
5. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`, `layers.acceleration.force-enabled`, `gfx.webrender.all`, and `svg.context-properties.content.enabled`. Make sure to enable them all!
6. Go to your thunderbird profile located in `$HOME/.thunderbird/XXXXXXX.default-release`.
7. Create the `chrome` folder, then assuming that you already clone this repo, just copy the content to the `chrome` folder.

## Note

If you're using Plasma and there's no blur effect,

1. Enable the blur in your compositor. Go to `System Settings > Desktop Effects > Enable Blur`. Note that this will not enable the blur effect on all applications.

2. Enable the blur effect on all applications by installing a KWin script called [Force Blur](https://store.kde.org/p/1294604/)

3. Go to `System Settings > KWin Scripts > Enable Force Blur`.

4. Finally, change the Thunderbird theme from default to dark. **This is important!**


It's been a while since I dwell with CSS so the theme is **kinda** messy right now. I'll clean this up from time to time, tho.
