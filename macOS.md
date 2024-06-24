# macOS Setup

## Enable dock autohiding without delay:
1. In settings, enable `Automatically hide and show dock` in _**Desktop & Dock**_
2. In terminal, run this command: `defaults write com.apple.dock autohide-delay -float 0; defaults write com.apple.dock autohide-time-modifier -int 0;killall Dock`

## Change screenshot output format to jpg
1. In terminal, run this command: `defaults write com.apple.screencapture type jpg`
