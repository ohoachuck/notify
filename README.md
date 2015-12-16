Notify - trigger AppleScript notification popup using a simple bash program
================


This script is a bash script that should work for OS X greater than or equal to Mavericks (10.9).
** **
This script use AppleScript command "[display notification](https://developer.apple.com/library/mac/documentation/AppleScript/Conceptual/AppleScriptLangGuide/reference/ASLR_cmds.html#//apple_ref/doc/uid/TP40000983-CH216-SW224)"


	Usage: 	notify 	[-t <Title>] 
					[-s <Subtitle>] 
					[-m <Message>] 
					[-a <Sound path>] 
					[- v (this is verbose mode)]


Example usage:

	notify -t "Demo Title" -s "This is Subtitle" -m "I love this convenient script" -a "Basso.aiff"
		
Where .aiff available sound files names could be found in /System/Library/Sounds/

### Known limits

Notification popup does show AppleScript icon. It's not possible to customize this icon. Unless you create your own AppleScript bundle using your custom icon ([see this thread](http://stackoverflow.com/questions/19627018/change-the-icon-of-an-applescript-called-notification)). But in this case this convenient (very simple) script would not make much sens.
