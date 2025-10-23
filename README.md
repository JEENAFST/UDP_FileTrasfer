UDP File Transfer – Quick Steps

Compile the programs

gcc udp_server.c -o server
gcc udp_client.c -o send


Run the server first

./server


Listens on port 8080 (or the port you set).

Run the client

./send


Default IP: 127.0.0.1 (localhost)

Default port: 8080

Default file: client.txt (or your own file)

Observe

Client prints [SENDING] lines.

Server prints [RECEIVING] lines.

Check received file

Server saves it as received.txt (or received_file).

cat received.txt


Optional

If client/server are on different machines, use server’s LAN IP instead of 127.0.0.1.

Ensure both devices are on the same network.
