This is a list of the software I typically install/configure on a new OS X build. 

#### First: Install OS X updates. 

## Install 

* [Chrome](http://google.com/chrome)
* [Evernote](http://evernote.com/download) (or App Store)
* [Sublime Text](http://www.sublimetext.com/2)
	* [Sublime Text Package Control](https://sublime.wbond.net/installation)
	* [Sublime Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview#installation-)
* [iTerm2](http://www.iterm2.com/)
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
* [git](http://git-scm.com/download/mac)
	* [Setup git](http://help.github.com/articles/set-up-git)
* [Node](http://nodejs.org)
* [Brew](http://brew.sh/)
* [Ruby](https://www.ruby-lang.org/en/installation/#homebrew)
* [Dropbox](http://www.dropbox.com)
* [1Password](https://agilebits.com/onepassword)
* [Quicksilver](http://qsapp.com/)
* Transmit (App Store)
* [Adium](https://adium.im/)
* Tweetbot (App Store)
* [HipChat](https://www.hipchat.com/)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](http://www.vagrantup.com/downloads.html)
* [Chef](http://www.getchef.com/chef/install/)
* [Bower](http://bower.io/): `$ sudo npm install -g bower`
* [Yeoman](npm install -g yo): `$ sudo npm install -g yo`
* xCode (App Store)
* GeekTool (App Store)
* Growl (App Store)
* [Charles](http://www.charlesproxy.com/)
* [Firefox](http://www.mozilla.org/en-US/firefox/new/)

## Configure

### iTerm2

To [toggle](http://coolestguidesontheplanet.com/show-hidden-library-and-user-library-folder-in-osx/) show/hide hidden files:  
Show: `$ defaults write com.apple.finder AppleShowAllFiles -boolean true ; killall Finder`  
Hide: `$ defaults write com.apple.finder AppleShowAllFiles -boolean false ; killall Finder`

1. `$ brew install wget`
2. Install [iTerm2](http://www.iterm2.com/).
3. Install [on-my-zsh](https://github.com/robbyrussell/oh-my-zsh).
4. Install fonts, [Source Code Pro for Powerline](https://github.com/Lokaltog/powerline-fonts/tree/master/SourceCodePro). Use the OTF fonts. 
5. Install these [three fonts](https://gist.github.com/qrush/1595572).
6. Copy remy theme to `~/.oh-my-zsh/themes` (use version in src).
7. Edit `~/.zshrc` to use the remy theme. `ZSH_THEME="remy"`
8. Install [iTerm theme](https://github.com/altercation/solarized/tree/master/iterm2-colors-solarized) (use customized version in src).
9. Turn off smart cursor color. 
10. Make sure the font is 15pt Source Code Powerline.
11. Adjust the vertical character spacing down slightly. 

### GeekTool

Modification is likely required to get these to work for you.

1. Open GeekTool, Enable, Check "Automatically launch at login". 
2. Create a new group.
3. Look in this repo under `src/GeekTool` for a Display or Laptop configuration. 
4. Update GmailUnread.glet with you Gmail username and password. 
5. Update RTMTasks.glet with the location of rememberthegeek.py.
6. Update [rememberthegeek.py](https://github.com/smenzer/geektool/blob/master/rememberthegeek.py) with the Atom URLs for the feeds you wish to display, and CACHE_DIRECTORY location.
7. Open each "geeklet" to add to your new group. 
8. Configure/tweak as needed.


## Miscellaneous

### Dock
* Enable magnification.
* Position Right.
* Auto hide/show dock.

### Trackpad
* Set "Tap to click" on Trackpad. 
* Turn off "natural" scroll direction.
* Set "Swipe between pages" to three fingers. 
* Increase trackspeed. 
