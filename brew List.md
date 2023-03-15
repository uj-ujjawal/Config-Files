# Homebrew Packages

This repo contains list of the most used app and how to install all of them with just few command instead of downloading and installing them one by one.

- First Install [HOMEBREW](https://brew.sh/) It is a package manager for LINUX and MAC OS.

## Most basic brew Command

- `brew serach <packageName>`  it will serach and display all available package with that name. For Example: `brew search firefox`
- `brw info <packageName>` if that packageName is valid then it will show the information related to that package like it's official homepage, etc. For Example: `brew info firefox`

**NOTE :** "CASK" specify apps (package) with GUI interface and "FORMULAE" specify apps (packages) with CLI interface.

To install App with GUI interface

- `brew install --cask <packageName>`  Example:  `brew install --cask firefox`

To install Apps with CLI interface

- `brew install <packagename>`  Example: `brew install git`

But in brew latest no need to specify --cask flag it will automatically indeify the package with name and install it eiterh it cask or formulae But if there is same package available as formule then it will install the formule package. So it is also okay to install GUI apps with this command `brew isntall firefox`

## How To install in bluk

`xargs brew install < file.txt`

## Fromulae

```
git
gh
gpg
gnupg
exa
tree
htop
wget
zsh-syntax-highlighting

yt-dlp
vcprompt
fortune
cowsay
wifi-password
python
nmap
ffmpeg
scrcpy
```

## CAKS

```txt
iterm2
sublime-text
openboard
cryptomator
iina
imageoptim
syncthing
discord
slack
shottr
obsidian
alt-tab
android-platform-tools
notion
appcleaner
audacity
protonvpn
commander-one
raycast
skype
firefox-developer-edition
spotify
folx
obs
android-file-transfer
canva
handbrake
visual-studio-code
whatsapp
google-chrome
foxitreader
blackhole-2ch
```
