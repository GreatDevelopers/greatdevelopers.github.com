**Apache vs Nginx (by Jugraj Singh)**

These are open source Web Servers.
50% of the Internet uses these two servers.
what is a web server:
	Is kind of a computer that serves other computers.
Apache:
	Normally used with LAMP
	Success of Apache:
		It came when the first gen of WWW came and hence became the industry standard.
		At that time the trafic was low
		Web pages were simple
		and bandwidth was low.
		Till 2005 apache was dominating the server world.
	Problem with Apache:
		C10K:
			Concurrently 10k clients requesting services from the server.
		To deal with this either we can buy more servers or use event driven I/O.
Nginx:
	It was created to solve the C10k problem. And does solve the problem.
	It uses Asynchronous architecture.
	It is event driven.
	It was created by Igor Sysoev. It is in C++.
	It became open source in 2004.

How apache works:
	For every new user there is new thread created which dedicated only to that user. This increases the load on the server CPU.
	Apache interprets the url as a file request by default. 
	
How nginx works:
	It does not create a new process for every new request. 
	A single working process can handle many requests.
	Nginx can also act as a shock absorber for Apache. So these can be used in conjunction.
	Nginx is immune to the Slowloris attack (DOS). 
	It is still under development.
	Nginx was also meant to be a proxy server. So mapping URLs into a file request is not the default behaviour.

Features needed in a server:
	Offers Static file serving.
	SSL/TLS support.
	Virtual Hosts.
	Reverse Proxying: A server represnting other servers to the clients.
	Load balancing: using reverse proxying.
	Compression: Compresses heavy web pages.
	Access control.
	URL rewriting.
	Custom logging..
	Server side ibcnludes.
	Limited WebDAV
	Video streaming.
	FastCGI.
	
Features of Nginx:
	Asynchronous
	Non-blocking: does not block users when a limit is crossed.
	Event-driven
	
Difference between the two:
	Apache is process driven but Nginx is event driven.
	Apache comes with the ability of being customized. Nginx is still new.
	Memory test proves that Nginx is better.
	CPU usage also proves thaat Nginx is better.
	Requests per second count is also high for Ngnix.

Questions:
	which is easier to use?
		Apache has a lot of tutorials on the web. Nginx does not.
	Which is better security wise?
		Apache.
	What is a rest server?
		A server which responds in JSON format.
	What is SSL/TSL:
		Secure Socket Layer.
	Who's response time is better?
		Nginx, maybe. Maybe Apache. 
