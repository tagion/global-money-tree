# Tagion WEB Explorer
This is a work in progress on creating an explorer for Tagion using subscriptino nng websockets for communication

## Plans
* Create WASM HiBON module which will be able to deserialize the streamed hibons directly. Currently you have to change the subscription to send HiBONJSON instead in order for it to work.
* REQ socket for interfacing directly with the shell and sending various dart requests such as `dartRead`...

