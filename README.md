# dotfiles

## osx config
- defaults write -g ApplePressAndHoldEnabled -bool false
- defaults write com.apple.finder AppleShowAllFiles -bool true
- defaults write com.apple.PowerChime ChimeOnAllHardware -bool false
- chflags nohidden ~/Library/
- Settings -> Keyboard -> Key repeat

## shell
- brew fish 
- omf install clearance
- omf install z
- alias xc "open *.xcworkspace || open *.xcodeproj" | funcsave xc
- alias gdf "git diff" | funcsave gdf
- alias rmdd "rm -rf ~/Library/Developer/Xcode/DerivedData/*" | funcsave rmdd

## apps
- iTerm2
- Spectacle
- Screenotate
- Atom
  - atom-notes (alt-cmd-l)
  - vim-mode-plus
- Xcode
  - XVim2 + .xvimrc
- Android Studio
  - Remap Cmd-Shift-O -> "Search Everywhere"
