# user-scripts

[![JavaScript Style Guide][standard-image]][standard-url]

User scripts for Tampermonkey and other user script managers (not tested yet)

# Image Viewer

[![IV file size][iv-size]][iv-url]


View full-size images from image hosts (e.g. Fastpic) w/o leaving the page or on a new tab w/o ads. Some image hosts disallow hotlinking. Such image host links are opened in new tab

:bulb: By default, script applies to all sites. I recommend enabling it only for specific sites. In Tampermonkey on script's settings tab uncheck `Original matches` and add your host's [masks](https://developer.chrome.com/docs/extensions/mv3/match_patterns/) in `User matches` (e.g. `https://myforum.net/*`)

## Changes in this fork

- Removed top & bot bars, only the image is left
- Global page-wide gallery, now all images on the page can be navigated (prev\next)
- Unlimited height for images
- 100% width for images
- Close image on double-click
- Transition animations & blurring removed

## Controls

### Keyboard:

- `←` - Previous image
- `→` - Next image
- `Esc` - Close image view

### Mouse:

- `double click` - Close image
- `click` on backdrop - Close image view

## Config

Available through the "Settings" script command at the Tampermonkey menu.

## Alternatives

- [Imagus](https://chrome.google.com/webstore/detail/imagus/immpkjjlgappgfkkfieppnmlhakdmaab)
- [Handy Image](https://sleazyfork.org/en/scripts/109-handy-image)
- [Imagehost Redirect](https://sleazyfork.org/en/scripts/2641-imagehost-redirect)

## Tools and Resources

- [Material Design icons](https://material.io/icons)
- [Material Design icons](https://materialdesignicons.com)
- [SVGOMG - SVGO's Missing GUI](https://jakearchibald.github.io/svgomg)
- [b64.io - image optimisation & base64 encode](http://b64.io)
- [Inkscape](https://inkscape.org/en/)
- [Material Design Button "ripple" effect animation (pure CSS)](https://codepen.io/lehollandaisvolant/pen/dMQXYX)
- [Keep a Changelog](http://keepachangelog.com/en/1.0.0)
- [Online regex tester and debugger: PHP, PCRE, Python, Golang and JavaScript](https://regex101.com)

[changelog-image]: https://img.shields.io/badge/-CHANGELOG-blue
[greenkeeper-image]: https://badges.greenkeeper.io/nikolay-borzov/user-scripts.svg
[greenkeeper-url]: https://greenkeeper.io/
[standard-image]: https://img.shields.io/badge/code_style-standard-brightgreen.svg
[standard-url]: https://standardjs.com
[iv-size]: https://img.shields.io/github/size/nikolay-borzov/user-scripts/dist/image-viewer.user.js.svg
[iv-url]: https://github.com/owyn/image-viewer/raw/master/dist/image-viewer.user.js
[iv-open-user-js-url]: https://openuserjs.org/scripts/nikolay-borzov/Image_Viewer
[iv-greasy-fork-url]: https://greasyfork.org/scripts/443464-image-viewer/code/Image%20Viewer.user.js
[jrdb-size]: https://img.shields.io/github/size/nikolay-borzov/user-scripts/dist/joyreactor-download-button.user.js.svg
[jrdb-url]: https://github.com/nikolay-borzov/user-scripts/raw/master/dist/joyreactor-download-button.user.js
[jrdb-open-user-js-url]: https://openuserjs.org/scripts/nikolay-borzov/JoyReactor_Download_Button
[jrdb-greasy-fork-url]: https://greasyfork.org/scripts/443465-joyreactor-download-button/code/JoyReactor%20Download%20Button.user.js
[ple-size]: https://img.shields.io/github/size/nikolay-borzov/user-scripts/dist/pornolab-enhancer.user.js.svg
[ple-url]: https://github.com/nikolay-borzov/user-scripts/raw/master/dist/pornolab-enhancer.user.js
[ple-open-user-js-url]: https://openuserjs.org/scripts/nikolay-borzov/Pornolab_Enhancer
[ple-greasy-fork-url]: https://greasyfork.org/scripts/443466-pornolab-enhancer/code/Pornolab%20Enhancer.user.js
[open-user-js-image]: https://img.shields.io/badge/OpenUserJS-install-304051.svg
[greasy-fork-image]: https://img.shields.io/badge/Greasy%20Fork-install-690001.svg
