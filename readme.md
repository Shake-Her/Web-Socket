# Web Sockets!

**While Creating a connection where we need a bidirectional connection between client and server eg: games,Chat app etc,This is a TCP connection! concept**

### Client/Server Connection "vs" Socket Connection

- Client/Server

![Client/Server](https://i.stack.imgur.com/uKIb7.png)

- Socket

![Socket Connection](https://upload.wikimedia.org/wikipedia/commons/1/10/Websocket_connection.png)

_As wer can see the normal HTTP is header is upgraded to new protocol of socket_

**DOCUMENTATION : The HTTP 1.1 (only) Upgrade header can be used to upgrade an already established client/server connection to a different protocol (over the same transport protocol). For example, it can be used by a client to upgrade a connection from HTTP 1.1 to HTTP 2.0, or an HTTP or HTTPS connection into a WebSocket.**

- For example, the client might send a GET request as shown, listing the preferred protocols to switch to (in this case "example/1" and "foo/2"):

````javascript
GET /index.html HTTP/1.1
Host: www.example.com
Connection: upgrade
Upgrade: example/1, foo/2```
````
