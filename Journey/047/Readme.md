# Building a Multi-Container Application #5

## Cloud Research
- Today, I've added custom Nginx to route each traffic to server or client appropriately. The following diagram below shows how the routing works.

<div align="center"><img src="diagrams-01 - nginx.png" width="1024px" /></div>

The Nginx routes traffics based on the prefixes, if a prefix is `api`, it will be routed to ExpressJS server. On the other hand, if it is root, it will be routed to React server.

## Social Proof
I'm not going to post my progression on social media.