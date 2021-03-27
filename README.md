# iterm2-conf
## setup
```
git clone git@github.com:yuyamada/iterm2-conf.git ~/.config/iterm2
defaults write com.googlecode.iterm2.plist LoadPrefsFromCustomFolder -bool true
defaults write com.googlecode.iterm2.plist PrefsCustomFolder -string "~/.config/iterm2"
sudo killall cfprefsd
```
