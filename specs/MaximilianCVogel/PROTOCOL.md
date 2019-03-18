### Specification : client-server communication

1. What transport protocol do we use?

TCP

2. How does the client find the server (addresses and ports)?

Let's choose the port 80

3. Who speaks first?

As soon as the connection's established, we'll have the client send a message

4. What is the sequence of messages exchanged by the client and the server?

it'll be an exchange of greetings like in the first lab with the bartender (something like :
hello - hi - how are you? - fine, you? - etc. until a certain point)

5. What happens when a message is received from the other party?

depending on where we're at in the sequence from point 4)

6. What is the syntax of the messages? How we generate and parse them?

we could send an xml document which can be parsed

7. Who closes the connection and when?

we'll have the client close the connection when our wanted sequence is done