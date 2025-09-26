# FATHOG

Fully Automated Troubleshooting and Health Optimization Gadget version 1

## Requirements

Powershell ISE 5.0 (Minimum)

Administrator rights for desktop usage.

## Notes
Version 1

Created by Evan Tiffany

Last Updated 06/2025

## SYNOPSIS

This application is used to retrieve data from an individual device and/or provide basic fix-actions to non-compliant computers.

This script was built on PowerShell 5. Does not yet include PowerShell 7 because the Air Force doesnt like us to have nice things; however, this should still work on PS7

This script WILL be run utilizing a CSA/desktop administrator account.

## INSTRUCTIONS
Copy and paste this script into PowerShell ISE as admin. Click the green arrow or press F5 on your keyboard.

If it provides an error and no image of a pig, close window (of applet not ISE) and rerun script. 

Once script is open, enter the computername into the top right where it says "enter computername" then click "Establish Connection!"

The log panel on the left-hand side will report success or failure. On success, you may run any actions you desire from the buttons on the right.

## KNOWN ERRORS
On initial run, the picture of the hog will sometimes not stream correctly into the application. Stop the program and rerun if this error occurs.

For the registry.pol button, if the file already exists in a .bak on the end user's equipment, it will not overwrite it.

Some buttons will return the correct data, but not include the computer name. Rest assured, the action DID run successfully on the computer you connected to.
## DISCLAIMER
This program will not 100% fix a device from running a few actions. The goal is to get updates to push into software center utilizing the 'check updates' button.
