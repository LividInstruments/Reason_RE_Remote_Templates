Reason_RE_Remote_Templates
==========================

Collection of Remote Templates for Propellerhead's Reason Rack Extensions.

Generously compiled by Koshdukai, these are simple templates for creating .remotemap files for all Reason Rack Extensions.
From the original forum post:
You're supposed to take this snippet and add it to your own controller's .remotemap file.
Then, edit it, replacing the "_control_" text with a valid control item identifier used by your own controller (check existing scopes on that .remotemap file or inspect the list in the respective Codec file).
Don't forget to replace the "//Map" for "Map" on each edited line, so your edited mappings become active.

If you want to combine all the templates into one file...
OS X: 
Open /Applications/Utilities/Terminal.app. 
Type "cd " (including space, no quotes), and drag the folder that has all these template files into the terminal window, which adds the complete path. Press enter.
Now type "cat *.txt > all.txt"
This combines all the .txt files in the current directory into a file named "all.txt"
WIN:
Start the command line terminal (cmd). 
Type "cd C:\Users\<username>\Documents\git\Reason_RE_Remote_Templates" (assuming that is the correct path!)
Now type "copy *.txt all.txt"
This combines all the .txt files in the current directory into a file named "all.txt"
Added to github June 25th, 2013 by Peter Nyboer.