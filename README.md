docker.io Mopidy - Spotify MPD Server
-------------------------------------

Simple MPD server with Spotify connection. 


Configure it
============

Copy the `mopidy.conf.dist` to `mopidy.conf` and edit it to fit your needs.

For complete configuration options, see http://docs.mopidy.com/en/latest/config/


Build it
========

docker build -t mopidy .


Run it
======

`docker run -d -p 6600:6600 -p 6680:6680 mopidy`


Ports
=====

* `6600` - MPD server
* `6680` - HTTP server
