CS 425 MP2 -- Multicast

Will Hennessy, Stephen Herring


A python, command line chat client that communicates via reliable multicast.

List all member IP addresses in config.txt, with the first line containing
the IP address of the number of your client.



Example:
We have created three config files: config1.txt, config2.txt, and config3.txt

In one terminal, execute
    python2 chat.py configs/config1.txt 1 1

In a second terminal, execute
    python2 chat.py configs/config2.txt 1 1

In a third terminal, execute
    python2 chat.py configs/config3.txt 1 1

Then each terminal can type in a message and it will be sent to all the others.