# Kotatogram – experimental [Telegram Desktop][telegram_desktop] fork.

[![Travis build status](https://img.shields.io/travis/kotatogram/kotatogram-desktop?label=Travis%20Build&style=for-the-badge)](https://travis-ci.org/kotatogram/kotatogram-desktop) [![Appveyor build status](https://img.shields.io/appveyor/ci/RadRussianRus/kotatogram-desktop?label=Appveyor%20build&style=for-the-badge)](https://ci.appveyor.com/project/RadRussianRus/kotatogram-desktop)

Original README with build instructions and licenses could be found in [Telegram Desktop repository][telegram_desktop_readme].

Also there is [updated instruction on how to build app in Ubuntu 16.04][docs_ubuntu_16].

There will be builds of Kotatogram for Windows and Linux 64-bit. No autoupdates for now.

Expect a lot of breaking changes.

## Changes

* Mention user by name, even if username was set (right mouse click on mention suggestion).
* Clickable links in user bios.
* Custom font start options:
  * `-mainfont` to set main font family (e.g. `-mainfont "Open Sans"`).
  * `-semiboldfont` to set semibold font family (`-semiboldfont "Open Sans Semibold"`).
  * `-semiboldisbold` - if you want set semibold font to be bold. If you pass `Open Sans Bold` to `-semiboldfont`, that won't work. You should use family name (e.g. `-semiboldfont "Open Sans" -semiboldisbold`)
  * `-monospacefont` to set monospaced font (e.g. `-monospacefont "Consolas"`)
* You can set "Nobody" in profile photo privacy.
* Minimum photo size in chat has been increased to 200px, so captions should be more readable.
* Maximum sticker size in chat has been decreased to 128px.
* Maximum caption field height has been increased to 150px (should fit about 5 lines).
* Allow interface scales `75-99` to be saved after restarting without start option.

[//]: # (LINKS)
[telegram_desktop]: https://desktop.telegram.org
[telegram_desktop_readme]: https://github.com/telegramdesktop/tdesktop/blob/dev/README.md
[docs_ubuntu_16]: https://github.com/kotatogram/kotatogram-desktop/blob/dev/docs/building-cmake-ktg.md