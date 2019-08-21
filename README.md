# Simple-TCP-Server-Client-CPP-Example
C++ socket example

Source code belongs to:
https://simpledevcode.wordpress.com/2016/06/16/client-server-chat-in-c-using-sockets/

To use on Linux:

Open terminal and copy-paste following lines:

```
cd INTO_CPP_FOLDER
g++ tcp-Server.cpp -o server
./server 8080
```
Open another terminal and copy-paste following lines:


```
cd INTO_CPP_FOLDER
g++ tcp-Client.cpp -o client
./client 127.0.0.1 8080
```
Note: This is for only Local usage.
