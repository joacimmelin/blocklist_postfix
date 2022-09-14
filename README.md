# blocklist_postfix
List of TLD:s that I block in postfix. I use this in ```/etc/postfix/sender_access.pcre``` which contains regex for dealing with the tld's and then call this from ```main.cf``` with the ```check_sender_access pcre:/etc/postfix/sender_access.pcre``` setting. 
