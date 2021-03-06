![CemUI Logo](https://i.imgur.com/FyFr81X.png)

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![Latest](https://img.shields.io/github/release/RedDuckss/CemUI/all.svg)
![Total Downloads](https://img.shields.io/github/downloads/RedDuckss/CemUI/total.svg)
![Star](https://img.shields.io/github/stars/RedDuckss/CemUI.svg?style=social&label=Star)

# What is CemUI?
**CemUI** is an easy-to-use, open source, game manager for the popular Wii-U Emulator, [Cemu](http://cemu.info/).

**Note:**
> CemUI v2.0 is currently a WIP and is not guaranteed to be stable.

# Screenshots
## Themes
![Themes](https://i.imgur.com/Oso0kmy.gif)

## Super Mario Maker Integration
![SMM Integration](https://i.imgur.com/WEswjZV.gif)

# Changelog & FAQ
### [Changelog](https://github.com/RedDuckss/CemUI/blob/master/CHANGELOG.md)

### [FAQ](https://github.com/RedDuckss/CemUI/blob/master/FAQ.md)


# How can I help? / I have a suggestion!
We **always** welcome suggestions and Pull Requests! This program is written in NodeJS and packaged with Electron. This means that anyone with experience in JavaScript, Node, HTML, CSS, and C++ can contribute just fine! With Node, C++ users can contribute as well, due to Node supporting C++ modules!
![Fork](https://img.shields.io/github/forks/RedDuckss/CemUI.svg?style=social&label=Fork)

**If you have a suggestion, and do not know any of the required languages, you can reach us on [Discord][1]**

# How to get the latest version of CemUI

The latest official builds can be found in the [GitHub Releases section](https://github.com/RedDuckss/CemUI/releases). These are stable builds.

To get the latest developer version of CemUI right now, you may build and run from source. These are more likely to be unstable.

To get the latest developer version, follow these steps:

1. Install [NodeJS](https://nodejs.org/)
2. Clone/Download this repo
3. Enter the source code directory via a command prompt (`cd C:/Path/To/CemUI`)
4. Run `npm i` to install all depends
5. Run `npm i electron -g` to globally install Electron
6. Run `electron .` in the source code directory. This will start the developer version of CemUI.

**This is the only official place that you can download CemUI, any other places hosting CemUI are doing it without our permission.**

# Themes
CemUI ships with 2 default themes, Fluent and Flux. Fluent is the original CemUI 2.0 design theme. Flux is our uniform theme following our own custom design specs, based on a mix of several existing specs.

# Custom Themes
CemUI supports loading 3rd party themes. Themes can be loaded from `%appdata%/CemUI/app_data/themes`. Each theme must have an `index.html` file, `config.json` file and a `thumbnail.jpg` file. `config.json` stores the basic settings for the theme. It is an object with these properties:

| Property | Description |
|----------|-------------|
| title | Theme name |
| description | Theme description |
| theme_color | Theme color (HEX) |

# Events
To fully utilize themes you will need to hook into the many events emitted (not all possible events are documented)
[See the Events section of the wiki for documentation](https://github.com/RedDuckss/CemUI/wiki/Events)

# I found a bug!
Given that this project is still very early in development, bugs will probably be common, and vary from person to person. If you find a bug, we ask that you follow this format for reporting the bug on the [Issue Tracker](https://github.com/RedDuckss/CemUI/issues) on the repo:
- A detailed name describing the bug (no "A bug happened" type titles!)
- A detailed description of the bug

- Exact steps to reproduce
- A screenshot/video of the bug/error message
- List games affected (if applicable)
- If possible, a video or gif showing the exact steps to reproduce (There are many free video recorders out there. It doesn't matter how you record it, as long as it's recorded)
- And above all: stay calm. Currently there are only 2 developers working on this project, and for one this is the first NodeJS app they have worked on. Also given the nature of how Electron packages apps, bugs may not occur on our end but will on yours. Please be patient while we attempt to fix the issue.

## Good bug report
![Good report](https://i.imgur.com/zjjLpn4.png)

## Bad bug report
![Bad report](https://i.imgur.com/9qM0lGy.png)

Found a bug? [Create an issue here!](https://github.com/RedDuckss/CemUI/issues/new)

# Credits
| Icon                                                    | Name                        | Credit                                                                           | Twitter                            | GitHub                           |
|---------------------------------------------------------|-----------------------------|----------------------------------------------------------------------------------|------------------------------------|----------------------------------|
| <img src="https://i.imgur.com/5QshX3v.png" height="32"> | RedDucks(s)/Jonathan Barrow | Founder/lead developer. Handles all backend functionality and maintains the API. | [Redducks Twitter](https://twitter.com/jondbarrow) | [Redducks GitHub](https://github.com/RedDuckss) |
| <img src="https://i.imgur.com/OFFt3eK.png" height="32"> | MrJVS                       | 2.0 co-founder. Handles all frontend functionality and presentation.             | [MrJVS GitHub Twitter](https://twitter.com/TWmrjvs)    | [MrJVS GitHub](https://github.com/mrjvs)     |
| <img src="https://i.imgur.com/Rc3lGbO.png" height="32"> | Somebody2804(BenTheHuman)   | UI/Frontend designer.                                                            |                                    |                                  |
|                                                         | dragnu5(Dragnus)            | Creator of over 400 custom images for CemUI.                                     |                                    |                                  |

[1]: https://discord.gg/EKn8HnW
