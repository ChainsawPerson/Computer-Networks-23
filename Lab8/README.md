# TELNET, FTP & TFTP
###### [Back](/)

**Warning:** You will need to connect to the University's Network for excercises 2 and 3

I used VPN for these [(provided by NTUA)](https://www.noc.ntua.gr/help/VPN)

## Important
For this excercise you will need to enable TELNET and TFTP Client:
- Open Control Panel by searching for control panel in the Start menu. ...
- Select Programs. ...
- Select Programs and Features.
- Select Turn Windows features on or off from the left pane.
- Select the check box next to Telnet Client.
- Select OK to enable Telnet.

Same for the TFTP Client

Now you will need to add a rule in the firewall to allow the tftp.exe:
- Open Control Panel by searching for control panel in the Start menu. ...
- Select System and Security -> Windows Defender Firewall -> Advanced Settings -> Inbound Rules
- New Rule... -> Program -> This program path: C:\Windows\System32\TFTP.EXE -> Allow the connection -> Check all -> Name it
- Enable the new rule

And you should be ready to go :D

Reminder to first enable TFTP Client before adding the rule, otherwise TFTP.EXE will not exist :)
