# ActivityPub-Notes

`ActivityPub` adds two layers:

1. Server To Server (Decentralized, so servers can cross-communicate with each other offering interoperability)
2. Client To Server Protocol (so users, including real-world users, bots, and other automated processes, can communicate with ActivityPub using their accounts on servers, from a phone or desktop or web application or whatever)

> ActivityPub implementations can implement just one of these things or both of them. However, once you've implemented one, it isn't too many steps to implement the other, and there are a lot of benefits to both (making your website part of the decentralized social web, and being able to use clients and client libraries that work across a wide variety of social websites).

## Definitions

#### Actor

> ActivityPub actors are generally one of the ActivityStreams Actor Types, but they don't have to be. For example, a Profile object might be used as an actor, or a type from an ActivityStreams extension. Actors are retrieved like any other Object in ActivityPub. Like other ActivityStreams objects, actors have an id, which is a URI. When entered directly into a user interface (for example on a login form), it is desirable to support simplified naming. For this purpose, ID normalization SHOULD be performed as follows:
