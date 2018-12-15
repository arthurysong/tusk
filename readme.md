<h1 align="center">
  <img src="media/logo.png" width="18%"><br/>Tusk
</h1>

<h4 align="center">
  🐘 Refined Evernote desktop app
</h4>

<div align="center">
  <a href="https://github.com/klaussinani/tusk">
    <img src="media/note-navigation.gif" alt="Tusk" width="95%">
  </a>
</div>

<p align="center">
  <a href="https://travis-ci.org/klaussinani/tusk">
    <img alt="Build Status" src="https://travis-ci.org/klaussinani/tusk.svg?branch=master">
  </a>
</p>

## Description

Tusk is an unofficial, featureful, open source, community-driven, free Evernote app used by people in more than [130 countries](https://snapcraft.io/tusk).

Come over to [Gitter](https://gitter.im/klaussinani/tusk) or [Twitter](https://twitter.com/klaussinani) to share your thoughts on the project.

Visit the [contributing guidelines](https://github.com/klaussinani/tusk/blob/master/contributing.md#translating-documentation) to learn more on how to translate this document into more languages.

You can find more desktop apps [here](#related-apps).

## Highlights

- Black, Dark & Sepia Themes
- Focus, Compact & Auto-Night Modes
- Local & Global Customizable Keyboard Shortcuts
- Export Notes as PDF & Markdown Files
- Note Navigation
- Yinxiang Support
- Cross Platform
- Scalable Interface
- Update Notifications
- Drag and Drop Files

## Contents

- [Description](#description)
- [Highlights](#highlights)
- [Install](#install)
- [Features](#features)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Development](#development)
- [Related Apps](#related-apps)
- [Team](#team)
- [Disclaimer](#disclaimer)
- [License](#license)

## Install

#### Github Releases

Head to the [releases](https://github.com/klaussinani/tusk/releases/latest) page and download the appropriate installer for your system.

#### Snap

Ubuntu Linux users can directly install through [Snap](https://snapcraft.io/tusk) `snap install tusk`

#### Homebrew

Macos users can directly install through [Homebrew Cask](https://caskroom.github.io/) `brew cask install tusk`

#### AUR

Arch Linux users can directly install through [AUR](https://aur.archlinux.org/packages/tusk/) `yaourt tusk`

#### Note

The version available on `Homebrew Cask` or `AUR` may not be the latest. If that is the case, please consider downloading directly from the [Github releases](https://github.com/klaussinani/tusk/releases/latest) page.

## Features

Visit the project [homepage](https://klaussinani.github.io/tusk) to view all features in detail.

- Auto Night Mode - Press <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>N</kbd> to allow Tusk to adjust to your environment.
- Black Theme - Activate it by pressing <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>E</kbd>.
- Compact Mode - Downsize the window to enter the mode.
- Custom Shortcut Keys - Navigate to `~/.tusk.json` or press <kbd>Cmd/Ctrl</kbd> <kbd>.</kbd> to modify any shortcut key. To reset delete `~/.tusk.json` & restart the app.
- Dark Theme - Activate it by pressing <kbd>Cmd/Ctrl</kbd> <kbd>D</kbd>.
- Drag & Drop Files - Attach files by dragging them to the app window.
- Export Notes as Markdown - Press <kbd>Cmd/Ctrl</kbd> <kbd>O</kbd> to save your notes as `Markdown` files.
- Export Notes as PDF - Press <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>E</kbd> to save your notes as `PDF` files.
- Focus Mode - Activate it by pressing <kbd>Cmd/Ctrl</kbd> <kbd>K</kbd>.
- Global Shortcut Keys - Enable them by using the `File` > `Enable Global Shortcut Keys` option.
- Note Navigation - Navigate your notes by pressing <kbd>Cmd/Ctrl</kbd> <kbd>Tab</kbd> / <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>Tab</kbd> or jump directly to one by using <kbd>Cmd/Ctrl</kbd> <kbd>1</kbd> - <kbd>9</kbd>.
- Note Printing - Press <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>P</kbd> to print your notes.
- Scalable Interface - Adjust the zooming factor by pressing <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>=</kbd> or <kbd>Cmd/Ctrl</kbd> <kbd>-</kbd>.
- Sepia Theme - Activate it by pressing <kbd>Cmd/Ctrl</kbd> <kbd>G</kbd>.
- Update Notifications - Customize the apps update checking frequency.
- Yinxiang Support - Login to Yinxiang by using the `File` > `Switch to Yinxiang` option.

## Keyboard Shortcuts

### Local Shortcut Keys

70+ local keyboard shortcuts. Toggle anything in a flash.

<details>
<summary>View all the available local keyboard shortcuts.</summary>

<br/>

Description                | Keys
-------------------------- | --------------------------
Toggle Window Menu         | <kbd>Alt</kbd>
Toggle Full Screen         | <kbd>F11</kbd>
Return to Notes            | <kbd>Esc</kbd>
Delete Note                | <kbd>Delete</kbd>
Toggle Dark Theme          | <kbd>Cmd/Ctrl</kbd> <kbd>D</kbd>
Toggle Sepia Theme         | <kbd>Cmd/Ctrl</kbd> <kbd>G</kbd>
Toggle Focus Mode          | <kbd>Cmd/Ctrl</kbd> <kbd>K</kbd>
New Note                   | <kbd>Cmd/Ctrl</kbd> <kbd>N</kbd>
Save Note                  | <kbd>Cmd/Ctrl</kbd> <kbd>S</kbd>
Set Reminder               | <kbd>Cmd/Ctrl</kbd> <kbd>E</kbd>
Search Notes               | <kbd>Cmd/Ctrl</kbd> <kbd>F</kbd>
Bold Text                  | <kbd>Cmd/Ctrl</kbd> <kbd>B</kbd>
Italic Text                | <kbd>Cmd/Ctrl</kbd> <kbd>I</kbd>
Underline Text             | <kbd>Cmd/Ctrl</kbd> <kbd>U</kbd>
Strikethrough Text         | <kbd>Cmd/Ctrl</kbd> <kbd>T</kbd>
Export Note as Markdown    | <kbd>Cmd/Ctrl</kbd> <kbd>O</kbd>
Insert Date-Time Stamp     | <kbd>Cmd/Ctrl</kbd> <kbd>;</kbd>
Toggle Settings            | <kbd>Cmd/Ctrl</kbd> <kbd>,</kbd>
Make Text Smaller          | <kbd>Cmd/Ctrl</kbd> <kbd>-</kbd>
Edit Shortcut Keys         | <kbd>Cmd/Ctrl</kbd> <kbd>.</kbd>
Reset Zoom Level           | <kbd>Cmd/Ctrl</kbd> <kbd>0</kbd>
Toggle Sidebar             | <kbd>Cmd/Ctrl</kbd> <kbd>\\</kbd>
Navigate to Next Note      | <kbd>Cmd/Ctrl</kbd> <kbd>Tab</kbd>
Toggle Tags                | <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>T</kbd>
Toggle Notebooks           | <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>N</kbd>
Jump to Note               | <kbd>Cmd/Ctrl</kbd> <kbd>1</kbd> - <kbd>9</kbd>
Change Font Size           | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>1</kbd> - <kbd>6</kbd>
Toggle Black Theme         | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>E</kbd>
Toggle Vibrant Light Theme | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>U</kbd>
Toggle Vibrant Dark Theme  | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>J</kbd>
Print Note                 | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>P</kbd>
Add Shortcut               | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>S</kbd>
Align Left                 | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>L</kbd>
Align Center               | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>M</kbd>
Align Right                | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>R</kbd>
Increase Indentation       | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>K</kbd>
Activate Auto Night Mode   | <kbd>Cmd/Ctrl</kbd> <kbd>Alt</kbd> <kbd>N</kbd>
Make Text Larger           | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>=</kbd>
Export Note as PDF         | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>E</kbd>
New Tag                    | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>T</kbd>
New Notebook               | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>N</kbd>
Toggle Checkbox            | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>B</kbd>
Code Block                 | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>L</kbd>
Add Link                   | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>K</kbd>
Attach File                | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>F</kbd>
Insert from Drive          | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>D</kbd>
Decrease Indentation       | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>M</kbd>
Numbered List              | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>O</kbd>
Toggle Shortcuts           | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>S</kbd>
Toggle Dev Tools           | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>I</kbd>
Reload Tusk                | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>R</kbd>
Set Always on Top          | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>P</kbd>
Insert Date Stamp          | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>;</kbd>
Bulleted List              | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>.</kbd>
Subscript Text             | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>]</kbd>
Superscript Text           | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>[</kbd>
Insert Horizontal Rule     | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>-</kbd>
Navigate to Previews Note  | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>Tab</kbd>
Remove Formatting          | <kbd>Cmd/Ctrl</kbd> <kbd>Shift</kbd> <kbd>Space</kbd>

<br/>

</details>

### Global Shortcut Keys

Access Tusk at any moment from anywhere within your operating system. All global shortcuts can be customized to match your own preference through the configuration file `~/.tusk.json`.

<details>
<summary>View all the available global keyboard shortcuts.</summary>

<br/>

Description                | Global Shortcut
-------------------------- | --------------------------
Toggle Tusk Window         | <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>A</kbd>
Create New Note            | <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>C</kbd>
Search Notes               | <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>F</kbd>

<br/>

</details>

## Development

For more info on how to contribute to the project, please read the [contributing guidelines](https://github.com/klaussinani/tusk/blob/master/contributing.md).

- Fork the repository and clone it to your machine
- Navigate to your local fork: `cd tusk`
- Install the project dependencies: `npm install` or `yarn install`
- Run Tusk on dev mode: `npm start` or `yarn start`
- Lint code for errors: `npm test` or `yarn test`
- Build binaries and installers: `npm run release` or `yarn release`

## Related Apps

- [Ao](https://github.com/klaussinani/ao) - Elegant Microsoft To-Do desktop app.
- [Taskbook](https://github.com/klaussinani/taskbook) - Tasks, boards & notes for the command-line habitat.

## Team

- Klaus Sinani [(@klaussinani)](https://github.com/klaussinani)
- Mario Sinani [(@mariocfhq)](https://github.com/mariocfhq)
- Thanasis Gkanos [(@ThanasisGkanos)](https://github.com/ThanasisGkanos)

## Disclaimer

Tusk is an unofficial, open source, third-party, community-driven, free app and is not affiliated in any way with Evernote.

## License

[MIT](https://github.com/klaussinani/tusk/blob/master/license.md)
