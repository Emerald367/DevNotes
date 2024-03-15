# NETWORK REQUESTS 

## What is a Network Request? 
    A network request communicated info between two or more pieces of hardware. Typically uses HTTP or HTTPS protocol. 
  Most common type is between a client and a server.

## HTTP & HTTPS
   Stands for HyperText Transfer Protocol (Secure). Is the primary protocol for communication and data transfer between web client and web server. 

## IP Addresses and Ports
   IP address identifies a machine or server in an IP network and determines the destination of a data packet. 

   Port numbers identify apps or services in a system. 

## Domains and URLS
  Universal Resource Locator
URL: https://www.twitter.com
Domain: www.twitter.com

## Rest Design and HTTP Methods
 GET: Give/get me info
 POST: Send package (creates child resource)
PUT: Send package (creates/replaces the resource)
PATCH: Send package (updates part of the resource)
DELETE: Delete the target resource

## Request Response Cycle [pt1]
Network request to a particular port of a server located by IP address

Port identifies connection endpoint;
directs data to a specific service

HTTP method determines the action to occur at a service. 

## RRC [pt 2]
Server executes code dependant on the HTTP method specified.

Server responds to the client with a status code and data (optional)

The client receives the response and the network request as fulfilled.

## Status Codes

1xx: Informational
2xx: Request was successful
3xx: Client is redirected to a different resource 
4xx: The request contains some kind of error
5xx: Server errored while fulfilling the request. 

## Headers

A field of an HTTP request or response that passes additional context and metadata about the request or response. 