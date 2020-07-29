# Freshwin10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gits from github. I also added default apps and other tools to the script that I install on every machine.

## My Additions

- Changed External Program Setup
- Fixed Syntax

## Modifications
Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```