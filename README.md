# Multi-client-chat-application-using-TCP-IP

Multi Client Chat Application Using Sockets

## To run the application

1) Create Server object file 

    Type the following command in your terminal : 
    ### gcc server.c -lpthread -o server

2) Run the server :

    Type the following command in your terminal : 
    ### ./server

3) Create Client object file :

    Type the following command in another terminal : 
    ### gcc client.c -lpthread -o client

4) Run the Client :

    Type the following command in another terminal : 
    ### ./client

    It will ask for an IP and PORT. The PORT is hardcoded as 8000
    but can be changed in the "client.c" file. You can set the IP to be the IP of the device
    you are running the server in (127.0.0.1 for localhost).

5) Run as many clients as you want in different machines
connected to the same network.

6) Enjoy!
