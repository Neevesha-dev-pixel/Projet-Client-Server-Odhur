# Projet-Client-Server-Odhur

This application has 3 requests to the server : 
1. A request to obtain a document available on the server 
2. A request to obtain the list of documents available on the server.
3. A request to delete a server document from the list.


When the client is connected to the server, the list of requests are displayed and can therefore choose the request that he wants either 1,2 or 3.
The connection can take place locally or on a LAN network (devices connected on the same sub-network)

# Installation 
To run the program, you will open a terminal on the folder where is located Client.c,Client1.c, Server.c and Server1.c  on different devices. 
 you will then run the following commands: 
  For the client : gcc -o Client-Server Client.c ,
                   gcc -o Client-Server Client1.c,
                   ./Client-Server
  For the server : gcc -o Client-Server Server.c,
                   gcc -o Client-Server Server1.c,
                   ./Client-Server 
# Author 
Odhur Neevesha Siwani 
