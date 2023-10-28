# __Communication in local network (Ethernet and ARP)__
###### [Back](/)

## IMPORTANT:
You will need to flush the ARP table in cmd

For me simply typing the __arp -d *__ command just wouldn't work (Windows 10)

Instead try this: __netsh interface IP delete arpcache__

After executing this once, it seems that __arp -d *__ also becomes usable or some time, which I'm guessing is until you restart your computer

### General comments from me:
This set was a bit more straightforward I guess but took *too* much time to write

Friendly tip: don't procrastinate for this as it might take you a while to write
