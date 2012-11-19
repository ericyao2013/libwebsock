libwebsock
==========

C library for easy WebSockets servers.

This library allows a developer to quickly develop WebSocket servers by focusing
on the actual logic of your WebSocket implementation instead of the details
of the WebSocket protocol or even specifics of C sockets.

To get started, have a look at echo.c in the root directory of the package.  A
simple echo server is implemented.

Features
========
* Callbacks for events
* SSL Support
* Easy to use
* Uses libevent for portability (tested on Linux/FreeBSD)
* IPv6 support
