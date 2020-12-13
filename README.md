# calculator
calculator created by command pattern 

you have a client that knows what nees to be done and a receiver that has the resources for doing it.

you want to package operations into self contained objects and pass them from client receiver 


Hur funkar det >

the cleint creates a command objekt that defines the command to be excuting , then. hands it over to the invoker which excutes the command , the executing command acts on the receiver 


benifits 


1- you can sote commands, queue operations, log operations and implement undo and redo operation 
2- you can change at runtime how a command is executedd wiout the client noticing 
