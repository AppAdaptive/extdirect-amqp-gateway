# extdirect-amqp-gateway

Server-side gateway for ExtJs applications using ExtDirect ((c) Sencha Corp.) as communication means. All ExtDirect client-requests are sent to an amqp-message-broker (we're using rabbitMQ 3.6.1), using the amqp-protocol (Version 0-9-1) and the message-broker response is then sent as ExtDirect response back to the client.

Thus it is possible to use ExtDirect-proxies in ExtJs applications while having at the same time the adavantages of a message-broker (security, scalability, distributability). 

The main ExtDirect features are a fork of https://github.com/jurisv/nodejs.extdirect 

If this package is used instead of the original nodejs.extdirect package, all examples of the example git-repository mentioned in the original packgage should work as well, provided a message-broker is used appropriately.

Developed and tested with rabbitMQ 3.6.1
