# Potential changes for GitHub

Browser extension that shows which pull requests contain changes related to a file.

> **Warning**: This extension is still in a very early stage and it serves as a proof of concept. Please keep that in mind when you use it.

## Install

* [Chrome extension](https://chrome.google.com/webstore/detail/potential-changes-for-git/neehipoljbecacjcgcceflmlikiadkob)

## Demo 

![Demo](demo.gif)

## Limitations

Currently, the extension has the following limitations:
- It is limited to Public repositories only.
- It is limited to repositories with 10 or less pull requests.
- GitHub has a rate limit of 60 requests per hour. Usually same requests are cached but if you want to check multiple files in different repositories, you can quickly "run out" of requests.

Most of the limitations above are there just because I wanted to save time and focused on solving the core idea behind this extension.

## Development

1. Go to [chrome://extensions/](chrome://extensions/) page
2. Toggle “Developer mode” in the upper right corner
3. Click the “Load unpacked” button
4. Select the folder with the source files

## Contributions

You're more than welcome to contribute. There are several things you can do:

* Submit a PR to one of the [issues](https://github.com/dzhavat/potential-changes-for-github/issues).
* Report bugs.
* Suggest new ideas.
* Suggest improvements to the code.
* Port the extension to another browser.
