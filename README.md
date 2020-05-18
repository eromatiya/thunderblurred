## Thunderblurred

### A ~~blurred~~ transparent CSS theme for Thunderbird. You need a compositor to have the blur effect.


| ThunderBlurred | Calendar |
| --- | --- |
| ![screenshot](images/mainwindow.png) | ![screenshot](images/calendar.png) |


## How to

### Quick install for the linux lads

```bash
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/manilarome/thunderblurred/master/install.sh)"
```

After the confirmation message that the theme is successfully installed, open Thunderbird. You'll notice that it is still not transparent. To fix this, go to **`Preferences > Extension and Themes > Change the theme to Dark`**.

#### NOTE:

It is advisible to check the script first before running it.

### Manual Installation

1. Open the Thunderbird Menu located on the top-right corner with a humburger menu(three horizontal lines).
2. Select `Preferences`, then `Preferences` again.
3. Go to `Advanced`, find the `Config Editor` button then press it.
4. A dialog will warn you, but ignore it, ~~just do it~~ press the `I accept the risk!` button.
5. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Make sure to **enable them all!**
6. Go to your thunderbird profile located in `$HOME/.thunderbird/XXXXXXX.default-release/`.
7. Create a folder and name it **`chrome`**, then assuming that you already clone this repo, just copy the theme to `chrome` folder.
8. Finally, change the Thunderbird theme from default to dark. **This is important!**

## Note

### If there's no blur effect


1. Make sure you have a compositor with blur support running! 

### If you're using Plasma and there's no blur effect,

1. Enable the blur in your compositor. Go to `System Settings > Desktop Effects > Enable Blur`. Note that this will not enable the blur effect on all applications.

2. Enable the blur effect on all applications by installing a KWin script called [Force Blur](https://store.kde.org/p/1294604/).

3. Go to `System Settings > KWin Scripts > Enable Force Blur`.


### If you're using Windows or Mac and something's wrong

1. I can't test it right now because I only have arch btw.

## TODOs:

- [ ] Fix UI inconsistencies
- [ ] Make all windows semi-transparent
- [ ] Clean up and remove redundancies
- [ ] Replace ugly icons
- [ ] Test it on different platforms