# 🔥 Fireside
Fireside is a stylesheet for Firefox that provides you with a clean UI. Less clutter, more vertical space.

![screenshot](https://github.com/bjesus/sidefox/assets/55081/ec3bd513-8ef1-465d-aa53-80384bcd0cce)

## Features
- Vertical tabs (using [Tab Center Reborn](https://addons.mozilla.org/en-US/firefox/addon/tabcenter-reborn/) or [Sidebery](https://github.com/mbnuqw/sidebery/))
- Zero UI elements taking vertical space
- Auto-collapsing sidebar preserving horizontal space and removing distraction
- Keyboard and mouse support

## Tested with
- Firefox 121 - 132.0b3, Linux (Wayland)

Contribute by submitting a PR for successful tests on other platforms or open an issue if unsuccessful.

## Installation
1. Go to `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
2. Install the [Tab Center Reborn](https://addons.mozilla.org/en-US/firefox/addon/tabcenter-reborn/) addon or [Sidebery](https://github.com/mbnuqw/sidebery/)
3. For Tab Center Reborn, in the addon settings, enable "Compact Mode" and copy the custom stylesheet from [here](tab-center-reborn.css)
4. In your Firefox Profile Directory (see `about:support` if you're not sure where it is) create a `chrome` directory and place the [userChrome.css](userChrome.css) file inside
5. Restart Firefox

## Usage
- Open the sidebar either using the mouse or by focusing on the location bar with `Ctrl+L`
- Back, Forward, Refresh, and other useless buttons were removed. Use touch gestures (two fingers slide), keyboard (`Alt+Left`, `Alt+Right`, `Ctrl+R`), or right click instead
- Extensions menus are available through the Extensions overflow button, on the right side of the location bar
