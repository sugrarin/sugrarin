## Apps

### Device Control
- [Karabiner Elements](https://karabiner-elements.pqrs.org) `/karabiner`
- [Macs Fan Control](https://crystalidea.com/macs-fan-control)
- [Monitor Control](https://github.com/MonitorControl/MonitorControl)
- [Mac Mouse Fix](https://macmousefix.com)
- [AlDente](https://apphousekitchen.com) / [BatFi](https://micropixels.software/apps/batfi)

### Design/Code
- [Figma](https://figma.com/downloads)
- [SF Symbols](https://developer.apple.com/sf-symbols)
- [Photomator](https://www.pixelmator.com/photomator)
- [Optimage](https://optimage.app)
- [ImageOptim](https://imageoptim.com)
- [Sublime Text](https://www.sublimetext.com) `/sublime-text`
- [VS Code](https://code.visualstudio.com) `/vscode`
- [Zed](https://zed.dev)
- [Plain Text Editor](https://sindresorhus.com/plain-text-editor)
- [Xcode](https://developer.apple.com/xcode)
- [DetailsPro](https://detailspro.app)
- [Interactful](https://hdthomas.com/apps/interact)
- [Github Desktop](https://github.com/apps/desktop)

### Other
- [Chrome](https://www.google.com/chrome/)
- [Alfred](https://www.alfredapp.com)
- [Artykul](https://artykul.org)
- [Telegram](https://desktop.telegram.org)
- [Things 3](https://culturedcode.com/things/)
- [Spotify](https://spotify.com)
- [ChatGPT](https://openai.com/chatgpt)
- [Rectangle](https://rectangleapp.com)
- [Warp](https://1.1.1.1)
- [Raindrop](https://raindrop.io)
- [Outline](https://getoutline.org)
- [Ekran](https://hands.do/ekran)
- [Maccy](https://maccy.app)
- [AnyDesk](https://anydesk.com)
- [Thor Launcher](https://github.com/gbammc/Thor)
- [Zoom](https://zoom.us)
- [Blender](https://www.blender.org/download)
- [Transmission](https://transmissionbt.com)
- [Cyberduck](https://cyberduck.io)
- [IINA](https://iina.io)
- [NetNewsWire](https://netnewswire.com)
- [Eagle](https://eagle.cool)
- [Black Out](https://sindresorhus.com/black-out)
- [Pearcleaner](https://github.com/alienator88/Pearcleaner)
- [Steam](https://store.steampowered.com/about)
- [Whisky](https://github.com/Whisky-App/Whisky)
- [Wireguard](https://www.wireguard.com)
- [Notability](https://notability.com)

## Settings

### Dock

Autohide:

```bash
defaults write com.apple.dock "autohide" -bool "true" && killall Dock
```

Remove the autohide delay:

```bash
defaults write com.apple.dock "autohide-delay" -float "0" && killall Dock
```

Do not display recent apps:

```bash
defaults write com.apple.dock "show-recents" -bool "false" && killall Dock
```

### Screenshots

Do not display the thumbnail:

```bash
defaults write com.apple.screencapture "show-thumbnail" -bool "false"`
```

Disable shadow:

```bash
defaults write com.apple.screencapture "disable-shadow" -bool "true"`
```

Do not include date:

```bash
defaults write com.apple.screencapture "include-date" -bool "false"`
```

### Desktop

Keep folders on top:

```bash
defaults write com.apple.finder "_FXSortFoldersFirstOnDesktop" -bool "true" && killall Finder`
```

### Trackpad

Light click weight:

```bash
defaults write com.apple.AppleMultitouchTrackpad "FirstClickThreshold" -int "0"
```
