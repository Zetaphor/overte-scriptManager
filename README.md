# Overte Script Manager

This is an application for use in [Overte](https://overte.org/).

This app provides an improved script manager experience complete with the ability to bookmark scripts for quick recall.

A copy of this script [is hosted here](https://overte.zetaphor.com/scripts/scriptManager/scriptManager.js), which can be loaded directly into Overte from the script manager.

### Hosting

The required files to host a copy of this script are as follows:

* scriptManager.html
* scriptManager.js
* output.css
* cash.min.js
* icon-active.png
* icon-inactive.png

The other files in this repo are not required to host an instance of this app.

### Dependencies

This script uses [cash.js](https://github.com/fabiospampinato/cash) for simpler selectors and [Tailwind CSS](https://github.com/tailwindlabs/tailwindcss) for CSS classes.

You can update the Tailwind CSS build output by installing `tailwindcss` with NPM and then running:

`npx tailwindcss -i tailwind.css -o output.css`
