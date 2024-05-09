# Project-Lowkey
Welcome to Project Lowkey, a repo designed to prevent DDOS attacks and trace them back to the attacker. 
## How Would We Trace These Attacks?
Well in a DDOS attack it can be 2 ways, the attacker is using proxies, or a botnet. 
## Whats a botnet?
A botnet is a chain of computers who all have ran a malicious file which adds them to a group of hundreds to thousands of computers in which the attacker can use to effictivaly overload just about any server. 
## Whats a proxy?
A proxy is an ip address someone can connect to, and hide their real IP to prevent IP blockage in a DDOS attack. 
## Well, how can you prevent these?
Lowkey will track your server traffic, if there is a sudden increase on outgoing connections by up to 50% we will protect the server, and these new IPs wont be served a page.
## How do we trace these?
Well, after the attack ends, those IPs are going to be added to a database where all sites who use Lowkey have built in, when an IP in this database loads a Lowkey webpage, the IP will get redirected to a page prompting that they were used in a DDOS attack and your urged to call a number where we can help the user find whatever software is runninng to keep them in this botnet, after we find it the executable is then debuged in a controlled enviorment so that we can obtain the IP of the server managing this botnet. This is when we hand this investigation to the police.
## When will this project luanch?
No clue, its going to take a while. 