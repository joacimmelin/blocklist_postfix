# blocklist_postfix
List of TLD:s that I block in postfix. I use this in ```/etc/postfix/sender_access.pcre``` which contains regex for dealing with the tld's and then call this from ```main.cf``` with the ```check_sender_access pcre:/etc/postfix/sender_access.pcre``` setting. 

Use at your own risk and make sure you don't mess up any other Postfix settings. There may already be a file called from the ```check_sender_access```setting so don't just blindly paste in the line above and expect magic. 
