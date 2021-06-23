# ARP-Implementation-Using-ADP
Performing ARP implementation using UDP, where we get the MAC address from the provided IP address in the input field when the network is the same.

Technical Objective –

Address Resolution Protocol (ARP) is implemented through this program. The IP address of any Client is given as the input. The ARP cache is looked up for the corresponding hardware address. This is returned 
as the output. Before compiling that Client is pinged.

Given Requirements –

There is a single host. The IP address of any Client in the network is given as input and the corresponding 
hardware address is got as the output.

Algorithm -

Client:

Step 1: Include the necessary header files.
Step 2: Create a socket using a socket function with family AF_INET, type as SOCK_STREAM.
Step 3: Bind the local host address to the socket using the bind function.
Step 4: Listen on the socket for connection requests from the client.
Step 5: Accept connection requests from the Client using accept function.
Step 6: Fork the process to receive a message from the client and print it on the console and 49
another process to read messages from the console and send it to the client simultaneously.
