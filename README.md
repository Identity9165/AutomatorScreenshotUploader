# Automator Screenshot FTP Uploader v0.1a

An macOS automator service that integrates itself to keyboard shortcuts
and uploads your screenshots to your FTP and copies the URL to your
clipboard. I wrote it because ShareX doesn't work on macOS.

## USAGE

1. Download the workflow
2. **Don't install it** yet, open it with Automator.
3. Select what kind of screenshot you want. You can duplicate the script to another keyboard shortcuts. 
4. Let's say you want Full Screen screenshot, select that.
5. Save to -> new -> Create a folder that you want to save your screenshots -> Save it as Untitled (or anything)
6. At the end there's a segment called run shell script, change the variables according to the comments.
7. Go to OSX Settings -> Keyboard -> Shortcuts Tab -> Select Services from the left and you'll see "AutomatorFTPUpload" service. Give it a shortcut and it's done.

## LICENSE

This program is available under the [WTFPL](http://www.wtfpl.net/) license.
