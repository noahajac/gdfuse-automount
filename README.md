# Google-Drive-Ocamlfuse Automount

Script that will mount Google Drive using [google-drive-ocamlfuse](https://github.com/astrada/google-drive-ocamlfuse). It searches the user's home directory for the folder `Google Drive` containing folders named the gdfuse labels. For example, my `/home/noahajac/Google Drive` looks like this:

    njacobson@student.[REDACTED].edu  noahajac@gmail.com  noah@noahjacobson.com

In google-drive-ocamlfuse, each of these directory names is a label distinguishing between different accounts.

The script will wait for internet connectivity (by pinging Google) before continuing. Also attached is [gdfuse.desktop](gdfuse.desktop) which can be placed in the `~/.config/autostart` directory in GNOME to run on login.
