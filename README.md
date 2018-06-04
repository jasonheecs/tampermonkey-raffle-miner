# Raffleminer.com Greasemonkey script

[![Build Status](https://travis-ci.org/jasonheecs/greasemonkey-raffle-miner.svg?branch=master)](https://travis-ci.org/jasonheecs/greasemonkey-raffle-miner)

A Greasemonkey / Tampermonkey user script that automatically enables cryptocurrency mining on [Raffleminer.com](https://www.raffleminer.com/) without needing user input when you visit the site.

## Prerequsities
You'll need to install one of the following browser extensions:

- [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) - For Chrome
- [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/?) - For Firefox

## Installation
Once the browser extension is installed, you can [install this user script via this link](https://greasyfork.org/scripts/369211-raffleminer-com-throttle-script/code/Raffleminercom%20throttle%20script.user.js).

## Usage
With this user script, visit [Raffleminer.com](https://www.raffleminer.com/). 

You can then set your NANO wallet address by clicking on the Tampermonkey / Greasemonkey browser extension in your toolbar and selecting the option "Set variable nanoWalletAddress". You can also set the max mining speed by changing the maxMiningSpeed variable, by default, the max mining speed is set to 10.

![Usage Demo](https://i.imgur.com/qJfXEsd.gif)