### About

Ricky's AppleScripts for iTunes.

### Install

	# Ensure ~/Library/iTunes/Scripts/ exists.
	mv Silent Growl-Enabled Whack Current Track.scpt ~/Library/iTunes/Scripts/

### Extra

These scripts shine when used with a global keyboard trigger. [Quicksilver](http://qsapp.com/) does this nicely.

### The Scripts

#### CloudTunes.scpt

Uploads the currently-playing track to CloudApp.

#### Silent Growl-Enabled Whack Current Track.scpt

AppleScript that, **without confirmation**, removes the currently-playing track from one's iTunes library and filesystem. It displays a Growl Notification. The name is an oxymoron. If the script were truly silent, it wouldn't notify you. Its "silence" refers to the lack of confirmation before deleting the track.

##### Credit

[Doug Adams's "Whack Current Track"](http://dougscripts.com/itunes/) AppleScript does all of the real work of these scripts. These are trivial, but useful, modification.
