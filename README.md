# KESTREL CHROME EXTENSION

A Chrome extension that helps you search on google more effeciently

## Setup development environment

- Clone the repo
- Run `yarn install` to install all packages

## Install the Chrome extension in development mode

- Start the yarn dev server: `NODE_ENV=development PORT=6002 yarn run start`
- Webpack will run and build the extensiob into `\build`
- Open Chrome and visit [chrome://extensions](chrome://extensions)
- Make sure developer mode is enabled on the top right corner of the page
- Click Load Upacked Extension on the left corner.
- Open the extension in the `\build` folder with manifest.json

## Build Chrome extension for release

- Run `NODE_ENV=production yarn run build` to build the extension
- Code will be built into the `\build` folder
