# Assignment 3 - README

## Description of files

### TCP/TCPclient.py   
The TCP client script

### TCP/server/TCPserver.py
The TCP server script for question 3

### TCP/server/TCPserver_with_sleep.py
The TCP server script for question 4

### UDP/UDPclient.py
The UDP client script

### UDP/server/UDPserver.py
The UDP server script for question 3

### UDP/server/UDPserver_with_sleep.py
The UDP server script for question 4

### .txt files in TCP/server and UDP/server
These are the files available on the server

#### Note: The client downloads files which are present in TCP/server or UDP/server and saves it in TCP or UDP folders respectively

## Instructions to run the files

### TCP/TCPclient.py   
`python3 TCPclient.py [buffersize in bytes] [disable Nagle's Algorithm?] [disable delayed ACK?]`      
For example:     
`python3 TCPclient.py 32 y y` will run the client with both Nagle's Algorithm and Delayed ACK disabled. (y for disabling, n for enabling).     
`python3 TCPclient.py 32 n n` will run the client with both Nagle's Algorithm and Delayed ACK enabled. (y for disabling, n for enabling).     

### TCP/server/TCPserver.py
`python3 TCPserver.py [buffersize in bytes] [disable Nagle's Algorithm?] [disable delayed ACK?]`    
For example:    
`python3 TCPserver.py 32 y y` will run the client with both Nagle's Algorithm and Delayed ACK disabled. (y for disabling, n for enabling).    
`python3 TCPserver.py 32 n n` will run the client with both Nagle's Algorithm and Delayed ACK enabled. (y for disabling, n for enabling).    

### TCP/server/TCPserver_with_sleep.py
`python3 TCPserver_with_sleep.py [buffersize in bytes] [disable Nagle's Algorithm?] [disable delayed ACK?]`    
For example:    
`python3 TCPserver_with_sleep.py 32 y y` will run the client with both Nagle's Algorithm and Delayed ACK disabled. (y for disabling, n for enabling).    
`python3 TCPserver_with_sleep.py 32 n n` will run the client with both Nagle's Algorithm and Delayed ACK enabled. (y for disabling, n for enabling).    

### UDP/UDPclient.py
`python3 UDPclient.py [buffersize in bytes]`    
For example:    
`python3 UDPclient.py 32`    

### UDP/server/UDPserver.py
`python3 UDPserver.py [buffersize in bytes]`    
For example:    
`python3 UDPserver.py 32`    

### UDP/server/UDPserver_with_sleep.py
`python3 UDPserver_with_sleep.py [buffersize in bytes]`    
For example:    
`python3 UDPserver_with_sleep.py 32`    

