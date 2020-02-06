# dotfiles

## osx config
- defaults write -g ApplePressAndHoldEnabled -bool false
- defaults write com.apple.finder AppleShowAllFiles -bool true
- defaults write com.apple.PowerChime ChimeOnNoHardware -bool true
- killall PowerChime
- chflags nohidden ~/Library/
- Settings -> Keyboard -> Key repeat

## shell
- iTerm2
  - Solarized
  - Input Mono Medium 14
- brew fish 
- install [oh my fish](https://github.com/oh-my-fish/oh-my-fish)
- omf install clearance
- omf install z
- alias xc "open *.xcworkspace || open *.xcodeproj" | funcsave xc
- alias gdf "git diff" | funcsave gdf
- alias gup "git pull --rebase" | funcsave gup
- alias gst "git status" | funcsave gst
- alias rmdd "rm -rf ~/Library/Developer/Xcode/DerivedData/*" | funcsave rmdd
- search for "Upgrading your Ruby version" -> "Setup with alternate shells"
- `vim ~/.config/fish/config.fish`

## apps
- Spectacle
- Xcode
  - XVim2 + .xvimrc
  - Input Mono Condensed 14
  - Trim trailing whitespace -> "Include whitespace only lines"
- Android Studio
  - Disable code folding outline + all "Collapse by default" options
  - Input Mono condensed 14
  - Appearance & Behavior > System Settings > Android SDK -> download API level 27
- VSCode


## VSCode
```
code --install-extension ms-vscode.Theme-TomorrowKit
code --install-extension vscodevim.vim
```

other extensions:
macros (geddski.macros)
(combine commands with kb shortcuts)
