docker.io Mopidy - Spotify MPD Server
=====================================

Simple MPD server with Spotify connection. 

**Currently non-functional. Working on Pulseaudio integration**

Clone it
--------

`git clone https://github.com/SkaveRat/docker-mopidy-spotify.git && cd docker-mopidy-spotify`


Configure it
------------

Edit the `mopidy.conf` to fit your needs. You need to at least enter your Spotify details.

For complete configuration options, see http://docs.mopidy.com/en/latest/config/


Build it
--------

`docker build -t mopidy .`


Run it
------

`docker run -d -p 6600:6600 -p 6680:6680 mopidy`


Ports
-----

* `6600` - MPD server
* `6680` - HTTP server
