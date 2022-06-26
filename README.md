qBittorrent sukebei.nyaa.si Search Plugin
==========================

This is a fork of [MadeOfMagicAndWires qBit-plugins](https://github.com/MadeOfMagicAndWires/qBit-plugins) lazily rewritten to search [sukebei.nyaa.si](https://sukebei.nyaa.si).

Installation
------------

Simply download the [plugin file](https://github.com/vt-idiot/qBit-SukebeiNyaa-plugin/raw/master/engines/sukebeisi.py). Grab the [Fav Icon](https://github.com/vt-idiot/qBit-SukebeiNyaa-plugin/raw/master/engines/sukebeisi.ico) if you want it. qBittorrent won't fetch it automatically because nyaa is using a 32x32 PNG Fav Icon.
This ICO file will also work for nyaa.si if you rename it appropriately - that should be nyaasi.ico if you're using the nyaa plugin this is forked from! 

After you've done this you can add this plugin to qBittorrent by going:

<kbd>Search tab</kbd> 🡪 <kbd>Search Plugins</kbd> 🡪 <kbd>Install a new one</kbd>  
<kbd>Local File</kbd> then select the plugin file you downloaded

Or by manually copying the `sukebeisi.py` and `sukebeisi.ico` to the following location:
  * Linux: `~/.local/share/data/qBittorrent/nova3/engines/`
  * Mac: `~/Library/Application Support/qBittorrent/nova3/engines/`
  * Windows: `%localappdata%\qBittorrent\nova3\engines\`

**The Fav Icon will only display if copied manually.** You must restart qBittorrent, or copy it before the .py file to see it show up immediately.

### License

All files are distributed under the GPL v3 license
