# CN-Lab
 String Reversal Server using UDP Sockets
 
1.Clone this repository to your local machine
2.Compile the server and client programs.
   gcc assg1_udp_client.c -o assg1_udp_client
   gcc assg1_udp_server.c -o assg1_udp_server
3.Run the server
   ./assg1_udp_server
4.In another terminal window Run the client
   ./assg1_udp_client
5.Enter the string you want to reverse in the client terminal.
6.The server will receive the string, reverse it, and send the reversed string back to the client.
7.Both the server and client terminals will display the sent and received strings.
