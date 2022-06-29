# Read 13

## Message Queues

### Socket.io Chat Example<sup>1</sup>

#### 1. Explain to a non-technical recruiter what the Chat Example (above) does.

It's like a game of telephone, but there's one person in the middle of a circle of a bunch of other people.  The person in the middle is always listening for if/when anybody on the outside circle says something, then repeats it to other, specific people, or to everybody in the circle as a whole.

#### 2. What proof of life are we getting on the backend from the above app?

Terminal messages indicating joins/disconnects

#### 3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

`broadcast`

### Rooms<sup>2</sup>

#### 1. What is a room and how might a room be useful?

A room is an arbitrary channel that sockets can `join` and `leave`

#### 2. How do you join a room?

Call `join` on the room you want to join

#### 3. how do you leave a room?

Upon disconnection, sockets `leave` all the channels they were part of automatically, and no special teardown is needed on your part.

### Namespaces<sup>3</sup>

#### 1. What is a Namespace and what does it allow you to do?

A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

#### 2. Each namespace potentially has its own what? (hint: 3 things)

* event handlers
* rooms
* middlewares

#### 3. Discuss a possible use case for separate namespaces

Having a special namespace for only certain authorized users

### Bookmarks

[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

### Footnotes

<sup>1</sup>https://socket.io/get-started/chat/

<sup>2</sup>https://socket.io/docs/v4/rooms

<sup>3</sup>https://socket.io/docs/v4/namespaces/

[Back](/reading-notes/401/401-TOC.html)