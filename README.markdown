### About

AppleScript that, **without confirmation**, removes the currently-playing track from one's iTunes library and filesystem. It displays a Growl Notification.

The name is an oxymoron. If the script were truly silent, it wouldn't notify you. Its "silence" refers to the lack of confirmation before deleting the track.

### Install

	# Ensure ~/Library/iTunes/Scripts/ exists.
	mv Silent Growl-Enabled Whack Current Track.scpt ~/Library/iTunes/Scripts/

### Credit

[Doug Adams's "Whack Current Track"](http://dougscripts.com/itunes/) AppleScript did all of the real work of this script. This is a trivial, but useful, modification.

### Extra

This script shines when used with a global keyboard trigger. [Quicksilver](http://qsapp.com/) does this nicely.
