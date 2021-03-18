# Server

Implemented a Client-Server Program, the goal of the Server is to get any string sent to it from the Client and check if the key exists in the file. 

Program Outline: 
1. Create a Server with a designated Port. Server reads a text file of keys. 
2. A Client is created using a SERVERADDRESS and the same Port
3. Server establishes a connction with Client and checks to see if the keys being passed by Client exist
4. If the Key being passed exists in the file, Server sends back the value of the key, otherwise sends back “NOT FOUND”. 

The programs runs with the following command lines:
  python Server.py PORT
  python Client.py SERVERADDRESS PORT
