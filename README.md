# BackUp
**BackUp** is a small bash script to backup files using [GNU tar](https://www.gnu.org/software/tar).

##### Features:
* [gzip](https://www.gzip.org) compression (default)
* [bzip2](http://www.bzip.org) compression
* [zstd](https://www.zstd.net) compression
* separate user and system backup archives
* send backups to Google Drive (needs [rclone](https://rclone.org))

For more information: `Backup --help`


# CMusNotification

**CMusNotification** is a small bash script to use with [cmus](https://cmus.github.io).

Usage: `:set status_display_program=CMusNotification` in *cmus* settings


# FirefoxCleanUp

**FirefoxCleanup** is a simple bash script to cleanup Firefox's sqlite3 databases from default profile.

Usage: `FirefoxCleanup`


# morse

**morse** is a small [Perl](https://www.perl.org) script that translates English text to [Morse code](https://en.wikipedia.org/wiki/Morse_code).

Input is either standard input or any text files.
Output is always standard output.

For more information: `perldoc morse`


# NotifySend

**NotifySend** is a small bash script to use with [notify-send](https://developer.gnome.org/notification-spec).

If it doesn't find a notification system, falls back to:
1. [rofi](https://github.com/davatorium/rofi)
1. [i3-nagbar](https://i3wm.org)
1. [xmessage](https://xorg.freedesktop.org)
1. [logger](https://github.com/karelzak/util-linux)
1. `echo` builtin command.

Usage: `NotifySend <title> <details>`


# PrintScreen

**PrintScreen** is a small bash script for taking screenshots with [import](https://imagemagick.org).

Usage: `PrintScreen <select|all>`


# RecordMyDesktop

**RecordMyDesktop** is a small bash script for screencasts with [recordmydesktop](http://recordmydesktop.sourceforge.net).

Usage: `RecordMyDesktop <select|all> <mute>`


# Xprop

**Xprop** is a simple bash/[GNU awk](https://www.gnu.org/software/gawk) script to show X Properties in terminal or in xmessage window.
