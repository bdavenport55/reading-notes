# Read 12

## Socket.io

### Web Sockets<sup>1</sup>

#### 1. What is a Web Socket?

A computer communications protocol that provides full duplex communication channels over a single TCP connection

#### 2. Describe the Web Socket request/response handshake and what happens once the connection is established.

Client makes WebSocket handshake request, server returns WebSocket handshake response. Client and server can send WebSocket data or text frames back and forth in full-duplex mode.

#### 3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

Request

### Socket.io Tutorial<sup>2</sup>

#### 1. What does the event handler `io.on()` do?

Handles connection/disconnection events

#### 2. Describe some possible proof of life or proof that the code works as expected

`Hello world` rendering on a webpage

#### 3. What does socket.emit() do?

The firing of custom events

### Socket.io vs Web Sockets Tutorial<sup>3</sup>

#### 1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

WebSocket is the protocol and Socket.IO is a library that works with WebSocket. WebSocket is to Git as Socket.IO is to GitHub

#### 2. When would you use Socket.IO?

To provide an interface when using WebSocket

#### 3. When would you use WebSockets?

To communicate in real time between clients and web servers

### OSI Model Explained<sup>4</sup>

#### 1. What are a couple of key takeaways from this video?

* 7 Layers
  * Application - Numerous application layer protocols
  * Presentation - Data encrypted from sender, encrypted on receiver side
  * Session - Uses helpers
  * Transport - Segementation, Flow Control, Error Control
  * Network - Logical Addressing, Routing, Path determination
  * Data Link - Logical addressing, physical addressing
  * Physical - Electrical signal, light (fiber), air (wifi)

### TCP Handshakes Explained<sup>5</sup>

#### 1. Translate the gist of this video to a non-technical friend

TCP is a protocol for communication. The client (you) send request to server to communicate and server sends back an acknowledgement. There is essentially a lot of back and forth saying "do you hear me? I hear you", which then opens a line of communication for server and client to send messages back and forth.

### Bookmarks

[Socket.io Documentation](https://socket.io/docs/v4/)
[Socket.io Server API](https://socket.io/docs/v4/server-api)
[Socket.io Client API](https://socket.io/docs/v4/client-api)
[Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

### Footnotes

<sup>1</sup>https://en.wikipedia.org/wiki/WebSocket

<sup>2</sup>https://www.tutorialspoint.com/socket.io/

<sup>3</sup>https://www.educba.com/websocket-vs-socket-io/

<sup>4</sup>https://www.youtube.com/watch?v=vv4y_uOneC0

<sup>5</sup>https://www.youtube.com/watch?v=xMtP5ZB3wSk

[Back](/reading-notes/401/401-TOC.html)