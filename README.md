#TCP Socket
##TCP Client
First I saved the content of 10 favorite sites with their corresponding url names in a folder called serverfile.
in TCP_Client i consider a client that uses the TCP socket to send a request to the server to download the html file. The client first receives the file name and file storage path from the user through the console and then sends the requested file name to the server via the socket.
The server first checks if the requested file is available.If the file is on the server, the server first sends a "200 ok" response code to the client and then sends the file to the client.
The client shows the code received from the server to the user in the console and saves the received file in the path received from the user.
If the file is not available, the server sends an error message in the heart of "404 Not Found" to the client and the client displays the message to the user in the console.