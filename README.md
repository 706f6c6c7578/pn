# pn
pn - post news articles to Usenet groups, anonymously.

Usage under Windows 10/11 with WSL installed:

Step 1. start tor, press Control-Z, write 'bg' in your Terminal and press Enter. 

Step 2. start socat.sh with ./socat.sh, press Control-Z, write 'bg' in your Terminal and press Enter.

After that create your article with all Headers and a Message Body and save it as msg.txt

Finally run pn.go with the following paramter: go run pn.go < msg.txt

In your Terminal you will see the connection to the News Server, via Tor and that the article was received.


