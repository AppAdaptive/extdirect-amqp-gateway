# extdirect-amqp-server

ExtDirect amqp server using ExtDirect ((c) Sencha Corp.) as communication means with web-clients. The whole ExtDirect communication is sent, using the amqp-protocol (Version 0-9-1) to a message broker and the message-broker response is then sent as ExtDirect response to the client.

The main ExtDirect package is a fork of https://github.com/jurisv/nodejs.extdirect 

If this package is used instead of the original nodejs.extdirect packages, all examples of the example github mentioned in the original packgage should work as well.

Developed and tested with rabbitMQ 3.6.1
