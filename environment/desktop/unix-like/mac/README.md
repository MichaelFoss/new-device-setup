# Mac Setup

## Settings

* System Preferences
  * Appearance
    * Show scroll bars: Always
  * Apple Intelligence & Siri
    * Apple Intelligence & Siri: Apple Intelligence: On
    * Siri Requests
      * Voice: British (Voice 1)
  * Control Center
    * Control Center Modules
      * Bluetooth: Show in Menu Bar
      * Sound: Always Show in Menu Bar
      * Battery
        * Show Percentage: On
      * Menu Bar Only
        * Spotlight: Don't Show in Menu Bar
      * Recent documents, applications, and servers: None
  * Desktop & Dock
    * Dock
      * Size: Large
      * Magnification: Large
      * Automatically hide and show the Dock: On
      * Show indicators for open applications: Off
      * Show suggested and recent apps in Dock: Off
    * Desktop & Stage Manager
      * Click wallpaper to reveal desktop: Only in Stage Manager
    * Windows
      * Drag windows to screen edges to tile: Off
      * Hold ⌥ key while dragging windows to tile: Off
    * Mission Control
      * Automatically rearrange Spaces based on most recent use: Off
  * Spotlight
    * Help Apple Improve Search: Off
  * Trackpad
    * Point & Click
      * Quiet Click: On
      * Force Click and haptic feedback: Off
      * Tap to click: On
    * Scroll & Zoom
      * Smart zoom: Off
    * More Gestures
      * Swipe between pages: Off
      * App Exposé: Swipe Down with Four Fingers
      * Launchpad: Pinch with thumb and three fingers: Off
* Right click all icons in Dock, Options > Remove from Dock

## Software

* [Rectangle](https://rectangleapp.com/) _(previously [Spectacle](https://www.spectacleapp.com/))_
* [Homebrew](https://brew.sh/)
  * Brews _(`brew install <formulaName>`)_:
    * `cask`
    * `direnv`
    * `mysql`
    * `nvm`
    * `wget`
    * `powerlevel10k`
      * Add `source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme` to `.zshrc` post-install
  * Casks _(`brew install --cask <caskName>`)_:
    * `qlmarkdown`
    * `qlvideo` _(open app in Applications after installing)_
    * `syntax-highlight` _(install with `--no-quarantine` flag)_
    * `youtube-to-mp3`
      * Latest version requires downloading and installing straight from MediaHuman's website;
        brewing causes YouTube downloads to fail
* [1password](https://1password.com/downloads/mac/)
* [VLC Media Player](https://www.videolan.org/vlc/download-macosx.html)
* [Audacity](https://www.audacityteam.org/download/mac/)
* [Cron](https://cron.com/download/macos/)
* [SimpleComic](https://apps.apple.com/us/app/simple-comic/id1497435571)
* [GIPHY Capture](https://apps.apple.com/us/app/giphy-capture-the-gif-maker/id668208984)
* [Hermes](https://hermesapp.org/)
* [Microsoft Remote Desktop](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466)
* Visual Studio Code
    * [Run `code` from the command line to launch Visual Studio Code](https://code.visualstudio.com/docs/setup/mac)
* [iTerm2](https://iterm2.com/downloads.html)
  * Startup
    * Window restoration policy: "Use System Window Restoration Setting"
      * Turn off "General > Close windows when quitting an app" in macOS System Preferences (see [here](https://iterm2.com/documentation-restoration.html) for why)
  * Closing
    * Check "Quit when all windows are closed"
  * Profiles
    * Profiles > Keys > General
    * Left Option key: Esc+
    * Profiles > Keys > Key mappings
      | FOR | ACTION | SEND |
      | --- | ------ | ---- |
      | ⌘ ← |"SEND HEX CODE" | `0x01` |
      | ⌘ → |"SEND HEX CODE" | `0x05` |
      | ⌥ ← |"SEND ESC SEQ" | `b` |
      | ⌥ → |"SEND ESC SEQ" | `f` |
    * Pointer Settings
      * Bindings
        * Remove all bindings
        * Add action for "Paste from Clipboard" and set to "Right button single click"
