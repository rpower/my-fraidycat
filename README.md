This is a personalised version of the excellent [**Fraidycat**](https://github.com/kickscondor/fraidycat).

## Changes

* Fixed Twitch feeds not working ([#191](https://github.com/kickscondor/fraidycat/issues/191))
* Fixed the + symbol being off-centre ([#186](https://github.com/kickscondor/fraidycat/pull/186))
* Removed sparklines, pinned statuses and the pencil icon (click on the feed favicons to go to the edit page)
* Removed the logo at the top
* Removed the importance bar (I used the importance feature, but in each tab I only have feeds of one 'type' of importance, so I have no need to swap between them after adding a feed)

## Installation

I've only tested my version as a Firefox extension on Windows. For my own benefit, this is how I build the extension:

### Building the Firefox / Chrome Web Extension

If you're checking out the code from Github, make sure you've installed
[git-lfs](https://git-lfs.github.com) first. Then, clone normally.

Then, to build the web extension, use:

    npm install
    npm run webext

### License

My modified version of Fraidycat is distributed under the Blue Oak Model License 1.0.0.
Read it [here](LICENSE.md).
