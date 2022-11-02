# Fresh Install on a new Mac

## Firefox
![Download Browser](https://www.mozilla.org/en-GB/firefox/new/)

Density: Compact  |
![Walkthrough Guide](https://support.mozilla.org/en-US/kb/compact-mode-workaround-firefox)

Extensions:
  - uBlock Origin
  - I don't care about cookies
  - Panorama Tab Group
  - Momentum

## HomeBrew:
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

brew install
  - htop
  - kitty
  - jetbrains-toolbox
  - postman
  - spotify
  - rectangle
  - sublime-text
  - vlc
  - slack

## XCode
![Download Link](https://apps.apple.com/us/app/xcode/id497799835?mt=12)

## System Preferences:
### Keyboard:
Modifier Keys: 🌐 / fn Key ➡ ^ Control Key

Text Input: 🇬🇧 British - PC

## Sublime Text 4:
Theme:

- Press: ⌘ + ⬆️ + 🅿️: Install Package
- ayu
- Color Scheme: ayu-dark
- Color Theme: ayu-mirage

## Generate SSH Key:
- `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
- **enter**
- **enter**
- `pbcopy < ~/.ssh/id_rsa.pub # Copies the contents of the id_rsa.pub file to your clipboard`
