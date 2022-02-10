# Getting Started with socket-io-example-crypto

An example to understand how socket.io works.
In this example, we have 5 popular crypto-currency (with fake values). Server makes changes on data and send them to client. Client shows data and changes.

## Content

In the project directory, you can see:

### socket-io-example-crypto-server

Server side of web-socket.
This section sets up a simple server. The server make changes on the coins data each 3 seconds and send data to client.

### socket-io-example-crypto-client

Client side of web-socket.
This section provide a simple front. The client listens to the server and gets data from server and shows them.
In client section, redux is used for state management.


