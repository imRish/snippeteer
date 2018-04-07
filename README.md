<p align="center">
  <img src="assets/img/logo.png" height="180" width="180" />
</p>

# SNIPPETEER [![Build Status](https://travis-ci.org/imRish/snippeteer.svg?branch=master)](https://travis-ci.org/imRish/snippeteer)
_**Snippets Anywhere**_

**SNIPPETEER** is a productivity tool that rescues you from retyping. It can quickly search the snippets you choose to store and paste them in all applications.

## Table of Contents

- [Download](#download)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Support](#support)
- [Contributing](#contributing)

## Download

The latest version of **SNIPPETEER** for macOS, Linux and Windows is available [here](https://github.com/imrish/snippeteer/releases).

**macOS 10.9+, Windows 7+ & Linux are supported.**

## Installation

To clone and run this repository you'll need Git and Node.js (which comes with npm) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/therishabhpandey/snippeteer.git

# Go into the repository
cd snippeteer

# Install dependencies
npm install

# Rebuild dependencies for Electron
npm rebuild --runtime=electron --target=1.8.4 --disturl=https://atom.io/download/atom-shell --abi=57

# Run app
npm start

# Build dist 
npm run dist 
```

## Usage

Download or build a release of SNIPPETEER.

Set up these shortcuts, which will be globally registered.     
- Add a snippet 
- Search for snippet

These **shortcuts should be accesible from everywhere** in your system, so make sure to not use shortcuts that may conflict with your focussed applications. After adding the snippets, you can use the search feature to find and paste the snippet in other applications like notepad, sublime, etc.

_For more examples and usage, please refer to the [Wiki](https://github.com/imRish/snippeteer/wiki)._

## Screenshots
<p align="center">
	<img src="https://github.com/imRish/snippeteer/blob/master/assets/img/screenshot.jpg" width="100%"></img>
</p>

## Support

Please [open an issue](https://github.com//imrish/snippeteer/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/imrish/snippeteer/compare/).