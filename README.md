<div align="center">
  <h1>
    Adskip Extension - click simulators to skip ads on sites that restrict use of script-level video blockers
  </h1>
</div>

## Installation
1. Clone the repository `git clone https://github.com/magicgrl111/adskip-extension.git`
2. Run `npm install`
3. Run `npm run build`


##### Load the extension in Chrome & Opera
1. Open Chrome/Opera browser and navigate to chrome://extensions
2. Select "Developer Mode" and then click "Load unpacked extension..."
3. From the file browser, choose to `adskip-extension/build/chrome` or (`adskip-extension/build/opera`)


##### Load the extension in Firefox
1. Open Firefox browser and navigate to about:debugging
2. Click "Load Temporary Add-on" and from the file browser, choose `adskip-extension/build/firefox`

## Developing
The following tasks can be used when you want to start developing the extension and want to enable live reload -

- `npm run chrome-watch`
- `npm run opera-watch`
- `npm run firefox-watch`


## Packaging
Run `npm run dist` to create a zipped, production-ready extension for each browser.

-----------
This project is licensed under the MIT license.
