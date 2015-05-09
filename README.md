FirefoxOS Vertical Home (With GaiaMod Next goodies).

Based on the prototype of the vertical homescreen for FirefoxOS.

Installation

Homescreens are currently certified apps, so you will need to build FirefoxOS to install it.

1 - Clone this repo into your gaia checkout:

git clone https://github.com/KevinGrandon/firefoxos-vertical-home.git apps/firefoxos-vertical-home

2 - Reset your device to install the homescreen:

PRODUCTION=1 make reset-gaia

3 - Enable it!

*/ NOTICE */

This also works installing it from the WebIDE (Firefox 36+).

Just clone or download the GaiaMod branch, uncompress it (if you downloaded the zip file) and add the root folder to your proyects on WebIDE. Currently debugging doesn't work.
