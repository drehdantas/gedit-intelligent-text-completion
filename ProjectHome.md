# This project has moved to github! #
# Please visit https://github.com/nymanjens/gedit-intelligent-text-completion #

<br /><br /><br />

# Gedit plugin: intelligent text completion #
This plugin tries to make your life more comfortable by automatically adding text that you probably would have typed anyway.

## Features ##
  * Auto-close brackets and quotes
  * Auto-complete XML tags
  * Detects lists and automatically creates new list items
  * Auto-indent after function or list

## Installation ##
### Gedit 2 (up till Ubuntu 11.04) ###
  1. Unpack the archive
  1. Put `intelligent_text_completion.gedit-plugin` and `intelligent_text_completion.py` inside `.gnome2/gedit/plugins/` in your home directory.  (create it if it doesn't exist yet)
  1. (Re)start Gedit.
  1. Go to Edit->Preferences->Plugins and check the box for Intelligent Text Completion

### Gedit 3.0-3.7 (Ubuntu 11.10 - 13.04) ###
  1. Unpack the archive
  1. Put `intelligent_text_completion.plugin` and `intelligent_text_completion.py` inside `.local/share/gedit/plugins` in your home directory. (create it if it doesn't exist yet)
  1. (Re)start Gedit.
  1. Go to Edit->Preferences->Plugins and check the box for Intelligent Text Completion

### Gedit 3.8 (Ubuntu 13.10 or higher) ###
  1. Get the newest version from svn and put it into `.local/share/gedit/plugins`:
```
  mkdir -p ~/.local/share/gedit/plugins
  cd ~/.local/share/gedit/plugins
  svn checkout http://gedit-intelligent-text-completion.googlecode.com/svn/trunk/gedit3-8/ gedit-intelligent-text-completion
```
  1. (Re)start Gedit.
  1. Go to Edit->Preferences->Plugins and check the box for Intelligent Text Completion


### Similar plugins ###
I bundled some similar plugins in [this project](http://code.google.com/p/gedit-improving-plugins/).

## Demo ##
<a href='http://www.youtube.com/watch?feature=player_embedded&v=67OINBPOOis' target='_blank'><img src='http://img.youtube.com/vi/67OINBPOOis/0.jpg' width='425' height=344 /></a>

## Screenshot ##
![http://gedit-intelligent-text-completion.googlecode.com/files/Screenshot.png](http://gedit-intelligent-text-completion.googlecode.com/files/Screenshot.png)