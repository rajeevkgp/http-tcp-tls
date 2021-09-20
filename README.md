# http-tcp-tls

Hussein playlist - https://www.youtube.com/watch?v=AlE5X1NlHgg&list=PLQnljOFTspQW4yHuqp_Opv853-G_wAiH-

In http 1.0 there was one http call and tcp connection would be broken after that. So for every http call, a new tcp connection was made. This was remedied in http 1.1, and keep-alive was added to tcp to transfer multiple http requests on a single tcp.

TLS Handshake work in this way:
* Cipher suite negotiation - client and server negotiate on the protocol version and cipher suite to be used for secure communication.
* Authentication - during the handshake the client (sometimes the server) validate that they are establishing a connection with the intended recipient of the message.
* Key Exchange - the client and server derive a session key that will be used for symmetric encryption of the data, once the TLS connection is established.

TLSv1.1 (2006) - 
