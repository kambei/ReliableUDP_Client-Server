# ReliableUDP
A client-server application written in C which implements the Selective Repeat protocol for an reliable transmission with UDP as a transfer protocol

## INSTALL:
	1) Make install.sh executable: $ chmod +x ./install.sh

	2) Run install.sh: $ ./install.sh

	3) Check that folders "ServerFiles" and "ClientFiles" are created,
		some sample files will be created too in ServerFiles folder.


## SERVER: 1) Run the server:
```
$ ./server <port> [-v] [-t] [-vt]
```
### Example: 
```
$ ./server 49300 -v
```
for HELP: ```$ ./server -h```

# CLIENT: ```1) Run the clie```nt:
```
$ ./client <ip> <port> <win_len> <loss_prob> <timeout> [-v] [-t] [-vt]
```
### Example: 
```
$ ./client 127.0.0.1 49300 10 0.4 30000 -v
```
for HELP: ```$ ./client -h```
