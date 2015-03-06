
ServerSocketExe
===============

Example of socket communication using java

Compiling
---------

		javac GreetingServer.java
		javac GreetingClient.java

Running
---------

	*Server:*
		java GreetingServer <port>
	*Client:*
		java GreetingClient <host> <port>


Example
----------

		$ java GreetingServer 6065

		Waiting for client on port 6065...
		Just connected to /0:0:0:0:0:0:0:1%0:64038
		Hello from /0:0:0:0:0:0:0:1%0:64038
		Waiting for client on port 6065...
		Socket timed out!

		$ java GreetingClient localhost 6065
		
		Connecting to localhost on port 6065
		Just connected to localhost/0:0:0:0:0:0:0:1:6065
		Server says Thank you for connecting to /0:0:0:0:0:0:0:1%0:6065
		Goodbye!



