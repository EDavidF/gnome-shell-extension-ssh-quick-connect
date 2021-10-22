PLEASE NOTE:
This is a fork of original by Josh Martens (https://github.com/ibrokemycomputer). It is only here so I could upload to the Gnome Extensions site (https://extensions.gnome.org/extension/3237/ssh-quick-connect/) the Gnome 40 compatible changes that Josh made but did not upload for quick/easy install/remove.
My changes are in the metadata file - name, uuid, etc, plus adding the screenshot here.

ORIGINAL README:
# Overview

Lists entries from your `~/.ssh/config` file, and launches them in the default terminal when clicked.

## TODO

- Watch for file changes. ([Answer](https://stackoverflow.com/a/19063834/9884099), [Docs](https://developer.gnome.org/gio/stable/GFile.html#g-file-monitor))
- Convert `spawn_command_line_sync....toString()` to `ByteArray.toString()`. ([See here for example](https://github.com/andyholmes/gnome-shell-extension-gsconnect/pull/193/files))
