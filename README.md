# Welcome to System Design Basics
This repo is for demonstrating key system design concepts as laid out below.

## Proxies

The word "proxy" per dictionary definition is to "act on behalf of". This concept in a distributed network architecture of servers where clients (users) interact with servers (web applications) via the Internet can broadly occur in 2 scenarios:

* Isolate clients from outside world (need arises for a Forward Proxy)
* Isolate web-servers from outside world (need arises for a Reverse Proxy)

### Forward Proxy

### Reverse Proxy

Reverse proxies are servers that situate themselves between the servers (running web-services) and the Internet. The Reverse Proxy server receives the client requests incoming from the internet towards the web-services and proxies the requests to different servers, thereby providing the following key capabilities:

  * Server Anonimity
  * DDoS Protection
  * Load Balancing
  * Caching
  * URL/ Content Rewriting

Examples of softwares that provide Reverse Proxy functionality are: NGINX and HAProxy

In this repo I demonstrate the setting up of NGINX as Reverse Proxy on AWS
