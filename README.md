# firefoxsetup

A shell script which downloads, installs and configures Firefox for maximum privacy

### What it does

* Remove current installed versions of Firefox
* Download the latest version of Firefox from [this](https://download.mozilla.org/?product=firefox-latest&os=linux64&lang=en-US) link
* Install Firefox in /opt directory
* Create empty profiles for all user directories in /home
* Set the search engine to DuckDuckGo
* Remove Firefox default extensions
* Download and install some privacy extensions
* (Optionally) Configure Firefox preferences

### Extensions

The following extensions will be installed:

* [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
* [uMatrix](https://addons.mozilla.org/en-US/firefox/addon/umatrix/)
* [CanvasBlocker](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/)
* [ClearURLs](https://addons.mozilla.org/en-US/firefox/addon/clearurls/)
* [Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/)
* [User Agent Switcher](https://addons.mozilla.org/en-US/firefox/addon/user-agent-string-switcher/)

### Preferences

You can provide a file containing Firefox preferences to be installed system-wide (that means, for all profiles):

```
firefoxsetup pref_file
```
