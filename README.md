docker-jnethack-server
======================

Dockerfile for Public JNetHack server

== Setup

    docker build -t jnethack-server .
    docker run --detach --name jnh --publish 23:23 jnethack-server

== References

- http://nethackwiki.com/wiki/User:Paxed/HowTo_setup_dgamelaunch
- http://nethack.wikia.com/wiki/Compiling
- http://qiita.com/KurokoSin/items/bbbfb4b4f9ee645418f1
