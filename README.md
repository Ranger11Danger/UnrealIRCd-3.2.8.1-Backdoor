# UnrealIRCd 3.2.8.1 Backdoor

This is a python version of a metasploit module that exploits a known vulnerability in UnrealIRCd 3.2.8.1

I know that this exploit is already well documented and easy to perform with a metasploit module but I wanted to work on my python scripting knowledge, (specifically interacting with sockets in python), and thought this would be a good way to start.

Please let me know where the code could be improved upon, or if there is a completely different way to go about it thats better.

The updated version of this code has the ability to select the type of reverse shell to be sent. Currently there are only 3: python, netcat, and a bash shell, these options are set with -payload. ex. python3 exploit.py 1.1.1.1 6667 -payload python
