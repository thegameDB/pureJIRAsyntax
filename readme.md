Place the unzipped directory "pureJIRAsyntax" into the Sublime Packages directory
- MacOs /Users/pjones/Library/Application\ Support/Sublime\ Text\ 3/Packages/
- Windows C:\Users\YourUser\AppData\Roaming\Sublime Text 3\Packages\User
- Linux - figure it out yourself 

To use, select the syntax by clicking in the lower right hand corner (most unsaved files will default to "Plain Text") and select PureJIRA 


The default Sublime color scheme, Monokai, works but the highlight color is hard to see on the noformat areas of text. 
I included a modified version of Monokai named MonokaiPureJira that will show up in Preferences - Color Scheme... that has a different "selected" color

##Release notes* 
- Initial beta release!

##Issues
- Auto complete 
	- Auto complete and snippets will appear (eg when you type {n or {p, you will see autocomplete box and pressing enter or tab will complete the tag with {norformat}). 
	- The "issue" is that it will also attempt to autocomplete any other words already in the file. Working to disable this
- Nested { noformat} in { panel} will display as a single norformat region instead of seperate noformat boxes inside a distinct panel. Somewhat easy fix for next releas
- Not all JIRA projects have been added to hightlight, the most common like ES, PURE, HW, CLOUD, etc have been added. 

