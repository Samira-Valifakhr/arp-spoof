Implement an ARP Spoofing using Python:

ARP Spoofing allows hackers to redirect the flow of packets. This is a very serious and powerful attack that allows hackers to read, modify and drop information. The reason why it is possible is that ARP is not very secure, clients can accept responses even if they did not send the request, and clients trust responses without any form of verification.

this tool can inject code into the browser of the target, see all the information that the client sends and receives, and more. In this case, first I need to create an ARP response and send it to the target, so that we can poison their ARP table.

library:
1- scapy: a powerful Python-based interactive packet manipulation program
