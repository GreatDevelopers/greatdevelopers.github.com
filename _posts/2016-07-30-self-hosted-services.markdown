---                                                                     
layout: post                                                            
title:  "Self hosted services"                                    
date:   2016-07-30 1:00 IST                                       
author: "Mandeep Singh"                                              
categories: presentation                                                
---

### How to develop an Instant Messanging App
Using what tools and what to consider it

### Features
App should send message to other users.
When messages should pop up after receiving.
Social integration.

Things to be considered

### Only two things are there:
Front end and back-end

We can develop using simple HTML, CSS and JS or other.

### Channel/Protocol

***Xmpp:*** Extensible messanging and presence protocol
Used by WhatsApp.

***Protocol:*** Set of tools
***Presence:*** Present, busy, away
***Messaging:*** Messages
***Extensible:***

### MQTT: MQ Telementary Transport
Small footprint in real time

### Socket:
connection establish between one and other.

How MQTT and Xmpp establish connection, then?

### Backend

Server and database

We need real time server (milli second response). Without any latency.

### Database
SQL and NoSQL

***Which one is better?***
NoSQL is better for large data. SQL is more simpler.

If we have unstructured data, then should use NoSQL.

***Vertical scaling (SQL):*** Add more features
***Horizontal scaling (NoSQL):*** add more db's in form of clusters

But we can use clustering in SQL too. Now what?

***Is PostGIS or PostGreSQL NoSQL?***

### Tools

***OTP (Open Telecom Platform)***
***Erlang:*** Specially designed for communication. Used in WhatsApp.

***OTP includes:***
Erlang interpreter, Erlang compiler, based on xmpp

Compiler is optionally open-source, language is always open-source.

***Ejabberd Server***
Robust, scalable XMPP server

We can have a complete WhatsApp like application in JS.

There is a clone of WhatsApp using JS as frontend and cloudboost as backend

***Ionic can make linux apps?***

Another option is Phonegap

Cordova is a base for phonegap and ionic

### Socket.io

JS framework used for making messaging applications like collaborative applications.

### Meteor
It can be also used to build realtime apps. Can be used be build Android/ios apps.

***Difference between IM and Realtime?***
We can use realtime in Instant messanging. Realtime is a concept like realtime computing and IM is an applications.

Google Play application: Threema

***How IM better/convenient than using emails?***

We can have web server, mail server. Why can't we have our own messanging server?
