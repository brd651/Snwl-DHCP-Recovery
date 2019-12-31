# Snwl-DHCP-Recovery
Wrote a little script to pull DHCP Configurations from a SonicWall TSR and output CLI commands

There was a little bug in the 6.5.4.5 that would delete DHCP scopes when toggling Management features. This tool was built to be able to quickly recover from the loss of the DHCP scopes. 

## Dependencies:
none

## How to Run:
Run the python file and a Tkinter window will pop up. 
Click on Select file
Click on Run

Now you can copy the entire output by clicking the "Copy Commands" button or you can manually copy each section yourself. 

## Additional Info:
Currently there is no DHCP Generic Options in the CLI output in there, if there is a request for that to be add I will do that. Right now for my use of this script, I do not have the need for those commands. 
