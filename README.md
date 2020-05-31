
# The Daily Advice Client

The Advice Guy is a server program that
offers up practical, inspirational tips
to get you through those long days of
coding.
We’re building a client for The Advice
Guy program, which pulls a message
from the server each time it connects.
What are you waiting for? Who knows
what opportunities you’ve missed
without this app.

## Daily Advice Client
This program makes a Socket, makes a BufferedReader (with the
help of other streams), and reads a single line from the server
application (whatever is running at port 4242)

## Daily Advice Server
So what’s it take to write a server application? Just a
couple of Sockets. Yes, a couple as in two. A ServerSocket,
which waits for client requests (when a client makes a
new Socket()) and a plain old Socket socket to use for
communication with the client.

![](/dailyAdvice.jpg)
