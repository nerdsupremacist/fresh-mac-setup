# How to set up a fresh Mac the way I like it

Here's a simple list of steps to set up a Mac the way I like it. My setup is pretty simple except for my very specific trackpad settings.

## Password Manager

- [ ] Install 1Password
- [ ] Set up 1Password using QR code from phone

## Settings

### Trackpad

- [ ] Enable Tap to Click
- [ ] Set Secondary Click to `Click in bottom right corner`
- [ ] Set Tracking Speed to Fast
- [ ] Enable three finger drag:
	- It's hidden in Accessibility > Pointer Control > Trackpad Speed

### Dock

- [ ] Disable `Show recent applications in Dock`

## Terminal

- [ ] Install Xcode CLI tools
	- `xcode-select --install`
- [ ] Install Homebrew
	- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
- Set up zsh
	- [ ] Install zsh
		- `brew install zsh`
	- [ ] Install oh-my-zsh 
		- `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
	- [ ] Run `upgrade_oh_my_zsh`
	- [ ] Download Powerline9K Theme 
		- `git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`
	- [ ] Install a compatible font from the [repo](https://github.com/powerline/fonts).
		- You were last using Inconsolata
	- [ ] Set font in terminal to compatible font
	- [ ] Download .zshrc from the Password Manager
- [ ] Download ssh keys from the Password Manager
- [ ] Download .vimrc from the Password Manager
- [ ] Download global .gitignore from the Password Manager

## Apps

- [ ] Install Xcode from the App Store
	- [ ] Enable Trimming of blank lines in Text Editing > Editing > While Editing
	- [ ] Set command click to jump to definition in Navigation > Command Click on Code
	- And to save you the trouble of debugging this for the millionth time:
		- [ ] Run `sudo xcode-select -s /Applications/Xcode.app/Contents/Developer`
- [ ] Install Slack from the App Store
- [ ] Install Telegram from the App Store
- [ ] Install AdGuard for Safari from the App Store
- [ ] Install Grammarly for Safary from the App Store
- Setup Alfred.
	- [ ] Run: `brew cask install alfred`
 	- [ ] Set Spotlight Shortcut to something else
 	- [ ] Set Alfred Shortcut to ⌘ + Space
 	- [ ] Turn on Clipboard History
 	- [ ] Hide hat on Window
 	- [ ] Hide menu bar icon
- [ ] Install Sequel Pro:
	- `brew cask install sequel-pro`
- [ ] Install VS Code:
	- `brew cask install visual-studio-code`
- [ ] Install MacDown:
	- `brew cask install macdown`
- [ ] Install Git Tower:
	- `brew cask install tower`
- [ ] Install JetBrains Toolbox:
	- `brew cask install jetbrains-toolbox`
- [ ] Install Docker:
	- `brew cask install docker`
- [ ] Install Chrome (just in case):
	- `brew cask install google-chrome`
- [ ] Install WhatsApp:
	- `brew cask install whatsapp`
- [ ] Install Discord:
	- `brew cask install discord`
- [ ] Install Steam:
	- `brew cask install steam`
- [ ] Install LaTeX:
	- `brew cask install mactex`
	- [ ] Add the LaTeX Workshop plugin for VS Code
- [ ] Install IntelliJ via JetBrains ToolBox

