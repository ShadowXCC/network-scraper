# network-scraper

Tool written in python (GO, or some other language) that probes a whole network, writes the data into a human readable format (excel, more specialized tools) and computer readable formatS (CSV?, Ansible Inventory, others need to be found to make this tool viable). This tool should be plugin based, increase price for more features, decrease for less. Also have a free tier. 

Things to probe for:
Mac Address, IP, if IP is static or dynamic, operating system, os version, if there are pending updates (software, os, other), cpu/ram/storage (both percent in use, and total)  This tool should work on Windows/Mac/Linux/Unix targets out of the box, with a planned feature adding support for IOS and Android 

Planned features: 
More probed data (list of installed software and their versions), multithreading, AI (idk yet, but its the buzzword for the modern age), add support for IOS and Android, add user controlled polling rates and scheduled probes 
