# WeeChat Notification Center
## Originally from [github/sindresorhus](https://github.com/sindresorhus/weechat-notification-center)
### This fork adds notifications for all messages, not just private ones

![screenshot](https://raw.github.com/ilyakava/weechat-notification-center/master/screenshot.png)

[WeeChat](http://www.weechat.org) script to pass highlights and all messages to the OS X 10.8+ Notification Center


## Getting Started

- Install [weechat](http://www.weechat.org), recommended:
    - `brew install weechat --with-python` (you'll need [homebrew](http://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/) and [python](http://docs.python-guide.org/en/latest/starting/install/osx/))
- Install [pync](https://github.com/SeTeM/pync): `pip install pync`
- Put `notification_center.py` in `~/.weechat/python/autoload/`

###TODO

- Make clicking on notification make the Terminal the active window
	- [`Notifier.notify('Hello World', activate='com.apple.Safari')`](https://github.com/alloy/terminal-notifier/blob/master/README.markdown) not doing it for whatever reason


## License

MIT License
(c) [Sindre Sorhus](http://sindresorhus.com)
