# Shell Shockers Better HUD: sidebar test build

Test build of [Shell Shockers Better HUD](https://github.com/Virojet/Shell-Shockers-Better-Hud-Mod) with the MODS tab laid out as a section sidebar.

## Install

1. Install Tampermonkey or Violentmonkey.
2. Open `Shell-Shockers-Better-Hud.sidebar-test.user.js` and install it.

This build has its own `@name` and no update URLs, so it installs beside the release script and never auto-updates. Disable the release script while testing so the two do not run together.

## Changes from the release (5.2.3)

- MODS tab: section sidebar with one section per page.
- Pause menu placement: the menu is measured against the top HUD (team scores, capture/spatula status, scoreboard, streak) whenever it opens and slides down just far enough to stop covering them, at any resolution. It never moves so far that PLAY leaves the screen.

Before publishing to the release repo, restore the release `@name`, `@downloadURL` and `@updateURL`.
