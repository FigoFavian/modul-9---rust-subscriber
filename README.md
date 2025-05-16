Some questions to be answered:

### a. What is amqp? 

AMQP aka Advanced Message Queuing Protocol is an open-standard, application-layer protocol designed for message-oriented middleware. It defines both the rules for structuring messages and the behavior of message brokers which enables different systems to exchange information reliably and asynchronously. By using a broker like RabbitMQ, AMQP provides guaranteed delivery, flexible routing , and more. 

### What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?  

This is a URI-style connection string that tells an AMQP client how to reach and authenticate with the broker:

a. Username (guest) the account name used to log in to the broker.
b. Password (guest) the secret associated with that account.
c. Host (localhost) the network address or hostname where the broker is running. In this case, localhost refers to your own machine.
d. Port (5672) the TCP port on which the AMQP service is listening 

In conclusion, guest:guest@localhost:5672 instructs your client library to open a connection to the AMQP broker at 127.0.0.1 on port 5672 and to authenticate using the username “guest” and password “guest.”
